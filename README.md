# Montgomery_Fleet_Equipment_Inventory
It is an Excel study for practice. The dataset (.csv) used in this work comes from the following source: [Montgomery County Fleet Equipment Inventory](https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr)

## Part 1: Clean and Prepare Data
In Part 1,
- **Column widths:** Sorted out the widths of all columns so that the data is clearly visible in all cells.
- **Empty rows:** Used the Filter feature to look for blanks and remove all empty rows from the data.
- **Duplicate records:** Used Remove Duplicates feature to look for and remove duplicated records from the data.
- **Spelling:** Checked for spelling mistakes in the data and fixed them.
- **Whitespace:** Used the Find & Replace feature to remove all double-spaces from the data.
- **Department names:** When the data was converted from its data source, the department names didn’t import correctly and they are split over two columns in the data. Used Flash Fill to reduce the department names to just one column, and then remove any unnecessary columns.

Result: 

![1](https://github.com/user-attachments/assets/f433ef26-5a89-4009-8042-6bb0e62ccf53)

## Part 2: Analyze the Data
In Part 2,
- **Format the data as a table:** Used the Format as Table option to format the data as a table.
- **Use AutoSum to calculate values:** Used AutoSum to find the following values for column ‘C’ and record each of the values:
  SUM
  AVERAGE
  MIN
  MAX
  COUNT
- **Create a Pivot Table:** Used the PivotTable feature to create a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department.
- **Sort the pivot table data:** Used the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count.
- **Make two more pivot tables:** Created two more identical pivot tables.

Result:

![2](https://github.com/user-attachments/assets/313186a7-98c6-4a4c-9c6e-dd8280ef3424)

![3](https://github.com/user-attachments/assets/3e279c3b-6861-44c0-805b-64138531f1ed)

![4](https://github.com/user-attachments/assets/b5f4dab2-a0b8-4aea-b7a2-d44ee95ecf5c)

![5](https://github.com/user-attachments/assets/df819fe5-4d96-46d3-b288-1596e8cf0653)

