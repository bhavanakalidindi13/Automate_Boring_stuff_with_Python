### Practice Questions Answers

1. The openpyxl.load_workbook() function returns a Workbook object.

2. wb.sheetnames workbook attribute gives a list of all sheetnames.

3. To retrieve the worksheet object for a sheet named 'Sheet1' we use wb.get_sheet_by_name('Sheet1').

4. To retrieve the worksheet object for the workbook's active shhet we use wb.get_active_sheet().

5. To retrieve the value in the cell C5 we use sheet['C5'].value 

6. To set the value in the cell C5 to "Hello" we use sheet['C5']='Hello'

7. To retrieve the cell's row and column as integers we use cell.row and cell.column respectively.

8. The sheet.max_column and sheet.max_row sheet attributes holds the highest column and row numbers with values in the sheet respectively.
The data type of these attributes is integer.

9. To get the integer index for column 'M', we need to call openpyxl.cell.column_index_from_string('M')

10. To get the string name for column 14 we need to call openpyxl.cell.get_column_letter(14)

11. To retrieve a tuple of all the cell objects from A1 to F1 we use sheet['A1':'F1']

12. To save the workbook to the filename example.xlsx we use wb.save('example.xlsl')

13. An Excel formula is set just like any other text value in a cell that is by setting the cell's value attribute to a string of the formula text.
Formulas begin with = sign.

15 . To set the height of row 5 to 100 we use sheet.row_dimensions[5].height=100

16 . To hide the column C we use sheet.column_dimensions['C'].hidden=True

17 . Column and row headers that are always visible to the user even as they scroll through the spreadsheet, are known as freeze panes.

18 . Five functions and methods to call to create a bar chart are
``` bash
 openpuxl.charts.Reference()
 openpyxl.charts.Series()
 openpyxl.charts.BarChart()
 chartObj.append(seriesObj)
 add_chart()
```
