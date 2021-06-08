
[![Everything Is AWESOME](http://img.youtube.com/vi/TmRFAP7xTwk/maxresdefault.jpg)](https://www.youtube.com/watch?v=TmRFAP7xTwk "Power Apps SharePoint Document Library Tutorial")
**Click image to view video**

# Power Apps SharePoint Document Library Browser

### Step 1
Create Document Library. (You can use existing Documents library)
<br>
Create a column of type **Choice** and name it **Status** <br>
Enable Content Type for Document Library.<br>
Add 2 single line of text columns and name them **hiddenIsFolder** and **hiddenFolderPath**<br>
Set default value of column hiddenIsFolder to **No**<br>
Set folder default values for hiddenFolderPath as show in video.<br>
Set hiddenFolderPath value for folders manually.


### Step 2
[Import App zip file](https://github.com/rdorrani/PowerApps/blob/master/LeaveRequestApp/LeaveRequestApp_20210602180703.zip) in Power Apps. 

### Step 3
Edit the App.<br>Remove the SharePoint data source from the App & add a new SharePoint data source connection pointing to your Document Library.<br> On App OnStart function set your document library relative path.  **Set(varCurrentPath,"Shared Documents/")**

