# SqlQueryTabularViewer
Tabular Data Display, Sortable, Filterable, Searchable and Retrieve from MySQL Database by using MySQL Query Command.

# Basic Setup
The first step is to have the right CSS and JavaScript files. Make sure you are including the Bootstrap CSS file, as well as the SQL Query Tabular Viewer, jQuery, Bootstrap and AngularJS JavaScript files, in the <head> of your web pages. jQuery, Bootstrap and AngularJS must be loaded before SQL Query Tabular Viewer JavaScript.
![Link CSS and JS](https://raw.githubusercontent.com/alvinvoonyn/SqlQueryTabularViewer/master/Screenshots/Link%20CSS%20and%20JS.png)

Configure your MySQL hostname, username, password and the database in the sql_query.php. This PHP must be configured properly in order to communicate to the MySQL server.
<br />
![Configure MySQL Server](https://raw.githubusercontent.com/alvinvoonyn/SqlQueryTabularViewer/master/Screenshots/Configure%20MySQL%20Server.png)

# Include SQL Query Command
In order to display data in tabular form, you are required to insert the SQL query command to retrieve the data from the database. Include the data-ng-sql and insert the command to it in your HTML page. Besides that, make sure data-ng-view is included after the data-ng-sql command.

Type of SQL Query Support: Select, Insert, Update, Delete
![SQL Query Command](https://raw.githubusercontent.com/alvinvoonyn/SqlQueryTabularViewer/master/Screenshots/SQL%20Query%20Command.png)

# Tabular Display
The data will be displayed in table form. The table is styled with Bootstrap table template. The table is created with dynamic rows and columns.
![Tabular Display](https://raw.githubusercontent.com/alvinvoonyn/SqlQueryTabularViewer/master/Screenshots/Tabular%20Display.png)

# Sortable
The data can be sorted to ascending or descending order. You can change the order by click on the title of the column in the table.
![Descending Order](https://raw.githubusercontent.com/alvinvoonyn/SqlQueryTabularViewer/master/Screenshots/Descending%20Order.png)

# Filterable
The data can be filtered by entering the data you want to search along with the column you want to filter with.
![Filter](https://raw.githubusercontent.com/alvinvoonyn/SqlQueryTabularViewer/master/Screenshots/Filter.png)

# About
The "SqlQueryTabularViewer" library was developed as partial fulfilment for completion of unit COS30043 – Interface Design & Development offered in Swinburne University of Technology, Sarawak Campus in Semester 1, 2017.
