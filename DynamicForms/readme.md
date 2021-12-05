
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


Add data as follows:
<table>
<tr> <td>Name</td> 	 <td>Text</td>	 <td>Yes</td>	 <td>NA</td></tr>
<tr> <td>Age</td> 	 <td>	Number	</td> 	 <td>No</td> 	 <td>	NA</td></tr>
<tr> <td>Enrolled</td> 	 <td>	Yes/No</td> 	 <td>	No</td> 	 <td>	NA</td></tr>
<tr> <td>Enrolled Date</td> 	 <td>	Date</td> 	 <td>	Yes	</td> 	 <td>NA</td></tr>
<tr> <td>Region</td> 	 <td>	Choice</td> 	 <td>	Yes</td> 	 <td>	North;South;East;West</td></tr>
<tr> <td>Email	</td> 	 <td>Text	</td> 	 <td>No	</td> 	 <td>NA</td></tr>
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
