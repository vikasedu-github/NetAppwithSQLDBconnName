To Sucessfully run this app, We need to setup a DB server and App Service on Cloud.
Use command from sql file to create some sample table in DB.
Copy the connection string from DB and create new connection string in App Service and name it.
Now use the connection string name of App Service in App Code at the place of "SQLConnection" at line 18 in "ProductService.cs" under Service folder. It's recommended way to establish connection with DB because we only need connection string with DB password.

Another way to use the connection string inside Azure DevOps. Copy complete connection string from App Service and paste inside App setting block as shown in below image.

<img width="985" alt="az" src="https://github.com/vikasedu-github/NetWebAppwithSQLDBusingConnectionString/assets/70229856/3211925a-7f55-4c14-b198-92f706162ce2">
