# Student Project Demo
This is based on Adam Freeman's PRO ASP.NET Core 3 book.

https://www.apress.com/gp/book/9781484254394

## Create Solution and Projects

    dotnet new globaljson --sdk-version 3.1.101 --output JoseStoreSln/OutdoorProducts  
    dotnet new web --no-https --output JoseStoreSln/OutdoorProducts --framework netcoreapp3.1
    dotnet new sln -o JoseStoreSln  
    dotnet sln JoseStoreSln add JoseStoreSln/OutdoorProducts   
    dotnet new xunit -o JoseStoreSln/OutdoorProducts.Tests --framework netcoreapp3.1  
    dotnet sln JoseStoreSln add JoseStoreSln/OutdoorProducts.Tests   
    dotnet add JoseStoreSln/OutdoorProducts.Tests reference JoseStoreSln/OutdoorProducts 
  
  ## Welcome screen screenshot
  ![firstscreenshot](https://github.com/josesison1/JoseStoreSln/blob/master/WelcomeScreen.PNG)

  ## Lab 1B Questions
1. What is Entity Framework?
Entity Framework is an object relational mapper (ORM) which is a tool that simplifies mapping between objects in your software to the tables and columns of the database.

2. What is a Connection String?
Connection string used by Entity Framework contain information used to connect to the underlying ADO.NET data provider that supports the Entity Framework.

3. What is a Database Context?
The Database context relates to Entity Framework by deriving from the class and simply incorporate Entity Framework based data access into the application.

4. What is a Model Repository?
It is a relational database that stores the metadata for projects and folders. 

5. Migration vs Scaffolding?
Scaffolding is a quick way to generate the CRUD operation in a standarized way, creating the necessary logic that lets your application interact with the database. Migration is to perform model updates throughout the entire application which lets you modify your database after the model has changed.
