
[![Everything Is AWESOME](http://img.youtube.com/vi/wQqetH2QLyk/maxresdefault.jpg)](https://youtu.be/wQqetH2QLyk "Power Apps Dynamic Forms")
**🎥 Click image to view video**

# POWER APPS DYNAMIC FORM

### Step 1
Create a SP list with the following name: **Form Template**

<table>
  <th>Column Name</th>  <th>Column Type</th>  <th>Comments</th> 
  <tr> <td>Title</td>  <td>Single line of Text</td> <td>This will be the default column that gets created in a SharePoint list</td> </tr>
  <tr> <td>Column Type</td>  <td>Single line of Text</td> <td></td> </tr>
   <tr> <td>Required</td>  <td>Single line of Text</td><td></td> </tr>
   <tr> <td>Choices</td> <td>Single line of Text</td> <td></td> </tr>
</table>


Add data as follows:
<table>
   <th>Title</th>  <th>Column Type</th>  <th>Required</th> <th>Choices</th>
<tr> <td>Name</td> 	 <td>Text</td>	 <td>Yes</td>	 <td>NA</td></tr>
<tr> <td>Age</td> 	 <td>	Number	</td> 	 <td>No</td> 	 <td>	NA</td></tr>
<tr> <td>Enrolled</td> 	 <td>	Yes/No</td> 	 <td>	No</td> 	 <td>	NA</td></tr>
<tr> <td>Enrolled Date</td> 	 <td>	Date</td> 	 <td>	Yes	</td> 	 <td>NA</td></tr>
<tr> <td>Region</td> 	 <td>	Choice</td> 	 <td>	Yes</td> 	 <td>	North;South;East;West</td></tr>
<tr> <td>Email	</td> 	 <td>Text	</td> 	 <td>No	</td> 	 <td>NA</td></tr>
  </table>
  
  ### Step 2
Create a SP list with the following name: **Form Results**

<table>
  <th>Column Name</th>  <th>Column Type</th>  <th>Comments</th> 
  <tr> <td>Title</td>  <td>Single line of Text</td> <td>This will be the default column that gets created in a SharePoint list</td> </tr>
  <tr> <td>Result</td>  <td>Multiple line of Text</td> <td></td> </tr>
   <tr> <td>Age</td>  <td>Number</td><td></td> </tr>
   <tr> <td>Enrolled</td> <td>Single line of Text</td> <td></td> </tr>
  <tr> <td>Region</td> <td>Single line of Text</td> <td></td> </tr>
</table>


### Step 3
[Import App zip file](https://github.com/rdorrani/PowerApps/blob/master/DynamicForms/DynamicForms_20211205225225.zip) in Power Apps. 

### Step 4
Edit the App.  <br>
Remove the data source connection to "Form Template"& "Form Results"<br>
Add new data source connection & connect to your newly created SharePoint Lists **Form Template** &  **Form Results**
<br> Save the App & Close the App
<br> Edit the App again and test.

