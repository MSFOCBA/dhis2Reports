
#General use
##ServiceTab
Because of excpetions an attribute serviceCode was added to datasets and indicatorGroups.  
When in the dropdown of services and a service is choosen only all the datasets with that service code and
all indicatorGroups with that servicecode will appear.
###TOC
There is below the dossier text a Toc of content with hyperlinks

#Structure

##Views 
Index is the start page but the service, dataset and indicatorGrp tab have been implemented using views, the views are defined in the app.js
This means each tab has each own html file.

##Controler
Each tab has each own controller which are all in the controler.js futher  section, elemenements, 
indicators are  child controler which are used by multiple parent controllers.

##Services
All Rest-calls are placed in services.js and implemented using angular resources. 

#To Do
1. Add main structure to app as definied in [dhis2 dev guid](http://dhis2.github.io/dhis2-docs/master/en/developer/html/dhis2_developer_manual_full.html#d6531e13445 "dev guide dhis2")
2. logout problem 
3. editor for dossier
4. security for dataset zzdossier
5. security for tabs

#Known bugs
1. logout problem
2. Copy link with view Anchor included.

