
[![Everything Is AWESOME](http://img.youtube.com/vi/0U5jax-zMIc/maxresdefault.jpg)](https://youtu.be/0U5jax-zMIc "Leave Request App Walkthrough")
**Click image to view video**

# Leave Request App Template

### Step 1
Create a SP list with the following name: **Leave Request**

<table>
  <th>Column Name</th>  <th>Column Type</th>  <th>Comments</th> 
  <tr> <td>Title</td>  <td>Single line of Text</td> <td>This will be the default column that gets created in a SharePoint list</td> </tr>
  <tr> <td>Detail</td>  <td>Multiple Lines of Text</td> <td></td> </tr>
   <tr> <td>From</td>  <td>Date and Time</td> <td></td> </tr>
   <tr> <td>To</td>  <td>Date and Time</td> <td></td> </tr>
  <tr> <td>Leave Type</td>  <td>Choice</td> <td>Choice values:<br>⛱️ Vacation<br>🤒 Sick Leave<br>🎈 Floating Holiday<br>⚖️ Jury Duty<br>💔 Bereavement</td> </tr>
   <tr> <td>Status</td>  <td>Choice</td> <td>Choice values:<br>Declined<br>Approved<br>Pending Manager Approval<br>Pending HR Approval</tr>
   <tr> <td>Manager</td>  <td>Person or Group</td> <td></td> </tr>
   <tr> <td>HR</td>  <td>Person or Group</td> <td></td> </tr>
   <tr> <td>Approval Comments</td>  <td>Multiple Lines of Text</td> <td></td> </tr>
    <tr> <td>Approval Link</td>  <td>Single Line of Text</td> <td></td> </tr>
</table>

### Step 2
[Import App zip file](https://github.com/rdorrani/PowerApps/blob/master/LeaveRequestApp/LeaveRequestApp_20210602180703.zip) in Power Apps. <br>Imported zip file will contain both the App & the flow. 

### Step 3
Edit the App.  <br>On App OnStart function, Set the HR Admin details as follows: **Set(HRManagerEmail, "place email of HR Admin here")** <br>Remove the SharePoint data source from the App & add a new SharePoint data source connection with your newly created “Leave Request” list. 

### Step 4
Go to flow.microsoft.com <br>Turn on the “Leave Request Approval Process flow” <br>Edit the flow and update the SiteURL action to point to your SharePoint site where the new “Leave Request” list has been created.
