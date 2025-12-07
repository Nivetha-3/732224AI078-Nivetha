Conditional Append Rows in Google Sheets:

Manual click → Read sheet → Check condition → Append to Sheet1 or Sheet2

Create a new workflow — Click + New and name it Conditional Sheet Append.

Add Manual Trigger — Add the Execute workflow trigger to start the workflow manually.

Add Google Sheets node — Add Get row(s) in sheet to read data from the sheet.

Connect nodes — Link Manual Trigger → Get rows.

Add IF node — Add an If condition to check a value from the sheet.

Configure condition — Set the rule for true/false branching (e.g., compare a column value).

Add Append Sheet1 node — Under the true output, add Append row in sheet1.

Add Append Sheet2 node — Under the false output, add Append row in sheet2.

Map fields — Map the required data to both append nodes.

Save workflow — Click Save.

Run the workflow — Click Execute Workflow to test the conditional appending.


![sheet](https://github.com/user-attachments/assets/270909e4-58fa-4e31-b4cd-9c0874ca506b)



