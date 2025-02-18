# Data Cleaning and Preparation using Google Sheets 

 **Example 1: Use conditional formatting to highlight blank cells**
 
Conditional formatting is a spreadsheet tool that changes how cells appear when values meet specific conditions.

Open the spreadsheet: https://docs.google.com/spreadsheets/d/16BE6vk-0ALYDLTiCDW5fCYcmmrPTenTCfvrnDuuaprI/edit?gid=1764281342#gid=1764281342

Select the range of cells to which you’ll apply conditional formatting.
In this example, you’ll select columns A through L, except for columns F and H. To select all columns except for F and H: 								

**a.** Select cell A to highlight column A. 																				

**b.** Hold down the SHIFT key and at the same time use your mouse to select cell E. This will highlight all the columns between A and E. 												

**c.** To select the remainder of the columns, hold down the CONTROL (Windows) or COMMAND (Mac) key while you select cells G, I, J, K, and L. 										

**d.** Columns A through L in your spreadsheet should be highlighted except Column F and Column H. 

From the menu, select Format, then Conditional formatting. The columns you’ve selected should turn a light shade of green, and a new Conditional format rules tool will appear. Additionally, the Apply to range field should indicate the cells you’ve selected. 

Next, apply a condition to these cells to change the cell color if the cell is empty. In the Format cells if drop-down, select Cell is empty.

Select the Formatting style field. Select a bright color from the drop-down to make the blank cells stand out.

Select Done.

**Example 2: Remove duplicates**
Remove duplicates is a spreadsheet tool that automatically searches for and eliminates duplicate entries from a spreadsheet. This is faster and easier than searching the data by scrolling through it.

Create a copy of your dataset by right clicking the Association ABC membership tab and selecting Duplicate. This is a good practice, as it protects against accidentally deleting important data. Continue working in the new sheet, Copy of Association ABC memberships.

In the menu, select Data, then Data cleanup, then Remove duplicates.

Check the box next to Data has header row.

Check the box next to Select All to inspect the entire spreadsheet.

Select Remove duplicates.

**Example 3: Format dates consistently**
Format dates to make all of the data in your spreadsheet consistent. This makes items easier to find and manipulate.

Select column J (Membership valid through), which contains dates.

From the menu, select Format, then Number, then Date.

**Example 4: Use split to separate data into columns**
The split menu option is helpful when you have more than one piece of data in a cell and you want to separate those pieces of data into different cells. 

Select column L (Certification). 

In the menu, select Data, then Split text to columns.

The delimiter (for example, a comma) will be automatically detected. 

If needed, specify the separator manually in the dropdown that appears in your spreadsheet.


