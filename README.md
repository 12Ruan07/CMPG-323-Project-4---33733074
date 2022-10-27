# CMPG-323-Project-4---33733074

The goal of the project is to create an automotive process for CRUD services using UiPath. It will allow the creation, viewing, editing, and deleting of records in the database. 
To ensure that the process works correctly, and as intended users need to make sure that they are logged out of the web application. 

To following is a sequence of how the actions will be performed with the process:
* Login into the webapp
* Add Zones
* View Zones
* Add Categories
* View Categories
* Add Devices
* View Devices
* Edit Devices
* Delete Devices
* Edit Zones
* Delete Zones
* Edit Categories
* Delete Categories

A testing mechanism is also implemented to ensure that the actions were executed. After the create, view, edit and delete action for every table (Zone, Device, Category) the results will be wrote to the same excel file under a sheet called “Test Summary”. If every action was successful the result “TRUE” will write to the sheet, otherwise the result will be “FALSE”

This process can be used to save time and the manage a database automatically as well as to test the actions to make sure that everything is working correctly and as intended.
