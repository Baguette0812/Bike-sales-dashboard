# Bike-sales-dashboard

### Task
Clean the data and create an interactive dashboard which covers potential key information.

### Steps Taken
The following are the steps taken to get the data sheet from start to finish
- Created 3 extra sheets; WorkingSheet, PivotTables, and Dashboard
- Copied all data from original sheet to WorkingSheet. Removed duplicates once in WorkingSheet
- Used find and replace to change the S, and M's into single and married in Martial Status column
- Used find and replace to change the M, and F's into male and female in the Gender column
- Ensured the income column was set to currency and decreaed the decimal twice
- Inserted a column named Age Brackets next to the Age column. Used the following formula to determine Age Brackets: =IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))
- Created 3 pivot tables in the PivotTables sheet. Added charts for all 3 pivot tables
- Used find an replace to change 10+ Miles into More than 10 miles in the Commute Distance column
- Removed gridlines from the Dashboard sheet and built the dashboard using the pivot table charts
- Created slicers for Marital Status, Region, and Education to work on all charts in the dashboard

### Dashboard
![Dashboard](https://github.com/Baguette0812/Bike-sales-dashboard/assets/106466704/6feb3fee-3116-4309-bdff-662a39242abb)
