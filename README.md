# automeetattendance
basic script using google sheets api and javascript for aoutomating the process of marking attendance in google meet lecturs and compare attendance against the google classroom roster for that particular course

Follow these steps to set up this quickstart:

Create a new Google Sheet.
From within your new sheet, select the menu item Tools > Script editor. If you are presented with a welcome screen, click Blank Project.
Delete the code in the script editor.
Click on the "Untitled project" project name, and rename to "Attendance."
Click Resources > Advanced Google Services.
In the dialog that appears, find and click the on/off switch for the Google Classroom API and the Admin Reports API.
Click the down arrow to the right of the Code.js file name.
Select Rename.
Rename the file to "Attendance."
Copy and paste the following code into the script editor:


Note: You must have admin permissions to successfully run this quickstart.

Follow these steps to try this quickstart:

Switch back to your spreadsheet and reload the page. An Options menu appears on the menu bar.
Click Options > Import Last 5 Courses. A dialog box appears indicating that the script requires authorization.
Click Continue. A second dialog box requests authorization for specific Google services. Click Allow. The spreadsheet now contains a sheet, represented by a tab at the bottom, for each of your last 5 courses. Each course has a list of course attendees in the first column and Google Meet IDs across the top row.
Click on one of the course sheets.
Click Options > Check Attendance on Current Sheet. Attendance is entered for the current course's Google Meet IDs.
Repeat steps 4 and 5 for the four other classes.

updates that are under progress
creqating a web app to display the attendance and other statistics in a graphical way
creating automation to remove the requirement of manually activating the addon
and sending automated mails based on customisable templates for reminder to absentees
