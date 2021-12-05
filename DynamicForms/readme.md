
[![Everything Is AWESOME](http://img.youtube.com/vi/wQqetH2QLyk/maxresdefault.jpg)](https://youtu.be/wQqetH2QLyk "Power Apps Dynamic Forms")
**🎥 Click image to view video**

# POWER APPS DYNAMIC FORMS

### Step 1
Create a SP list with the following name: **Form Template**

<table>
  <th>Column Name</th>  <th>Column Type</th>  <th>Comments</th> 
  <tr> <td>Title</td>  <td>Single line of Text</td> <td>This will be the default column that gets created in a SharePoint list</td> </tr>
  <tr> <td>Column Type</td>  <td>Single line of Text</td> <td></td> </tr>
   <tr> <td>Reuqired</td>  <td>Single line of Text</td><td></td> </tr>
   <tr> <td>Choices</td> <td>Single line of Text</td> <td></td> </tr>
</table>

### Step 2
[Import App zip file](https://github.com/rdorrani/PowerApps/blob/master/EditableGrid/PowerAppsGridwithBulkCapabilities_20210921184658.zip) in Power Apps. 

### Step 3
Edit the App.  <br>
Remove the data source connection to "Task Assignments".<br>
Add new data source connection & connect to your newly created SharePoint List **Task Assignments**
<br> Save the App & Close the App
<br> Edit the App again and test.

# BULK IMPORT CSV
[Bulk Import CSV File](https://github.com/rdorrani/PowerApps/blob/master/EditableGrid/DataImport.csv)
