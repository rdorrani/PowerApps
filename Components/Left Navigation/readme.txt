Video Walkthrough - https://youtu.be/dP74npyyvGc

Step by step walkthrough of building a responsive Left Navigation Component.

Canvas components make it easier to build reusable controls, such as navigation menus and dialogs. 

The ‘master’ / ‘instance’ behavior makes it easy to reuse them as building blocks inside the app or shared between apps.

By creating a component library, app makers easily share and update one or more components with other makers.

Download component: https://github.com/rdorrani/PowerApps/tree/master/Components/Left%20Navigation

**** 2 things I missed showcasing in the video (It is part of the component available for download) which will highlight the current element selected in the Left Navigation Gallery
1) galNavigation Default property set to LookUp(LeftNavigation.NavItems,Screen=App.ActiveScreen)
2) rectSelected Visible property set to
ThisItem.IsSelected
