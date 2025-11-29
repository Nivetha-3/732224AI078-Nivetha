Form submission → Add row in Sheet → Email notification

Create workflow — Click + New, name it Form to Sheet Email.

Add Form Trigger — Add On form submission node and select your form.

Add Google Sheets node — Add Append row in sheet.

Connect nodes — Link Form Submission → Append Row.

Configure Sheet — Select Spreadsheet + Worksheet to store the form data.

Map fields — Map form inputs to sheet columns.

Add Sheets Trigger — Add Google Sheets Trigger (rowAdded) to detect new rows.

Connect trigger — Connect Sheets Trigger → Gmail.

Add Gmail node — Add Send a message under Gmail.

Configure Gmail — Add To, Subject, Body, include sheet data in the email body.

Save workflow — Click Save.

Test workflow — Submit form → Row added → Sheets Trigger fires → Email sent.


![WhatsApp Image 2025-11-29 at 6 59 28 PM](https://github.com/user-attachments/assets/652bf54d-b82c-456c-9d23-82674a512ccb)
