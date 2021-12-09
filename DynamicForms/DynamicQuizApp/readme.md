
[![Everything Is AWESOME](http://img.youtube.com/vi/wQqetH2QLyk/maxresdefault.jpg)](https://youtu.be/wQqetH2QLyk "Power Apps Dynamic Forms")
**🎥 Click image to view video**

# POWER APPS DYNAMIC QUIZ

### Step 1
Create a SP list with the following name: **Results**

<table>
  <th>Column Name</th>  <th>Column Type</th>  <th>Comments</th> 
  <tr> <td>Title</td>  <td>Single line of Text</td> <td>This will be the default column that gets created in a SharePoint list</td> </tr>
  <tr> <td>Response</td>  <td>Multiple lines of Text</td> <td></td> </tr>
   <tr> <td>Score</td>  <td>Number</td><td></td> </tr>
    <tr> <td>Total</td>  <td>Number</td><td></td> </tr>
</table>
  
### Step 2
[Import Quiz Template excel file to OneDrive](https://github.com/rdorrani/PowerApps/blob/master/DynamicForms/DynamicQuizApp/FormTemplateTabs.xlsx) 

### Step 3
[Import App zip file](https://github.com/rdorrani/PowerApps/blob/master/DynamicForms/DynamicQuizApp/DynamicQuizApp_20211209060253.zip) in Power Apps. 

### Step 4
Edit the App.  <br>
Fix connection for SharePoint or Excel Online if prompted.<br>
Remove the data source connection to "Results"<br>
Add new data source connection & connect to your newly created SharePoint List **Results**<br><br>
Remove the data source connection "Quiz"<br>
Add new data source connection for Excel Online (Business) & connect to your newly added Excel file in OneDrive for Business **FormTemplateTabs.xlsx**<br>
Choose Table "Quiz" & Connect.<br>
Unique column for Quiz - select Title & Connect.<br>
<br> Save the App & Close the App
<br> Edit the App again and test.

