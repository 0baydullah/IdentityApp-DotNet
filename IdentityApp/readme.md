#  Identity Framework
-------
### 1 . Add Identity to Project
- add Layout page (Master Page)
- Select Features you want to add in Identity
- Create Data Context Class which is used to communicate with database
- create User Class
### 2 . After adding Identity there will be a folder named "Areas"

### 3 . Add Register /Login Linkes in the Navbar(In Layout page we have to add "_LoginPartial.cshtml by partial tag")
### 4 . Add properties in ApplicationUser class
### 5 . Register these properties or configure in ApplicationDbContext class
### 6 . Add Connection String in "appsettings.json"
### 7 . Add-Migration and Update-Database
	```
	Server=MACHINEX\\SQLEXPRESS;Database=CodeFirstDB;Integrated Security=True;Encrypt=False;Trust Server Certificate=True"
	```
### 8 . Add fields in View