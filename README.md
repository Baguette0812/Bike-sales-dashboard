# Bike-sales-dashboard

### Task
Clean the data and create an interactive dashboard which covers potential key information.

### Steps Taken
The following are the steps taken to get the data sheet from start to finish
- Created 3 extra sheets; WorkingSheet, PivotTables, and Dashboard
- Copied all data from original sheet to WorkingSheet. Removed duplicates once in WorkingSheet
- Used find and replace to change the S, M, and F's into Single, Male, and Female in both the Martial Status and Gender columns
- Ensured the income column was set to currency and decreaed the decimal twice
- Inserted a column named Age Brackets next to the Age column. Used the following formula to determine Age Brackets: =IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))
- 
