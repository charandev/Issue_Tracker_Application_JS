# Issue_Tracker_Application_JS
This is a simple Application which takes Issues from the user and displays on the screen.
This application is live on http://issuetracker-com.stackstaging.com/

This is a simple issue tracker application and as you can see the user interface is split up into two sections. On top an input form is visible. By using the input fields for Description, Severity and Assigned To the user is able to enter new issues. The issues are stored in the Browser’s Local Storage. The list of existing issues is printed out in the bottom area. Here you can see that each issue is printed out with the details of description, severity and assigned to. In addition you can see that the issue is identified by a unique issue id. The issue is a GUID which is generated when the issue is created and stored in the Local Storage as well.
 Furthermore each issue has a status assigned. By default the status is “Open”. If an issue is resolved the user is able to set the status to “Closed” by using the Close button. The issue can be deleted from the list (and from Local Storage) by clicking on button Delete.
