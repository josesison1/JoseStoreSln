# Chapter 7 - Student Project Demo
This is based on Adam Freeman's PRO ASP.NET Core 3 book. 

https://www.apress.com/gp/book/9781484254394

---

## Create Solution and Projects

    dotnet new globaljson --sdk-version 3.1.101 --output JoseStoreSln/OutdoorProducts  
    dotnet new web --no-https --output JoseStoreSln/OutdoorProducts --framework netcoreapp3.1
    dotnet new sln -o JoseStoreSln  
    dotnet sln JoseStoreSln add JoseStoreSln/OutdoorProducts   
    dotnet new xunit -o JoseStoreSln/OutdoorProducts.Tests --framework netcoreapp3.1  
    dotnet sln JoseStoreSln add JoseStoreSln/OutdoorProducts.Tests   
    dotnet add JoseStoreSln/OutdoorProducts.Tests reference JoseStoreSln/OutdoorProducts 
  
  ---
  
  ## Welcome Screenshot
  ![firstscreenshot](https://github.com/josesison1/JoseStoreSln/blob/master/Sports%20Store%20Screenshots/WelcomeScreen.PNG)
  
  ## Products Screenshot
  ![products](https://github.com/josesison1/JoseStoreSln/blob/master/Sports%20Store%20Screenshots/Products.PNG)

  ## Bootstrap Screenshot
  ![bootstrap](https://github.com/josesison1/JoseStoreSln/blob/master/Sports%20Store%20Screenshots/bootstrap.PNG)
  
---

  ## Lab 1B - Sports Store Questions (1-5)
1. What is Entity Framework?
__Entity Framework is an object relational mapper (ORM) which is a tool that simplifies mapping between objects in your software to the tables and columns of the database.__

2. What is a Connection String?
__Connection string used by Entity Framework contain information used to connect to the underlying ADO.NET data provider that supports the Entity Framework.__

3. What is a Database Context?
__The Database context relates to Entity Framework by deriving from the class and simply incorporate Entity Framework based data access into the application.__

4. What is a Model Repository?
__It is a relational database that stores the metadata for projects and folders.__

5. Migration vs Scaffolding?
__Scaffolding is a quick way to generate the CRUD operation in a standarized way, creating the necessary logic that lets your application interact with the database. Migration is to perform model updates throughout the entire application which lets you modify your database after the model has changed.__

---

# Chapter 8 
---
## Categories Fig 8-5.
  ![cart](https://github.com/josesison1/JoseStoreSln/blob/master/Chapter%208%20Screenshot/categories%208-5.PNG)

---
## Add to Cart/Shopping Cart Fig 8-10. & Fig 8-11.
  ![fig](https://github.com/josesison1/JoseStoreSln/blob/master/Chapter%208%20Screenshot/Add%20to%20cart%20button%208-10.PNG)
  ![figs](https://github.com/josesison1/JoseStoreSln/blob/master/Chapter%208%20Screenshot/8-11.PNG)

---
## Test Cases Complete
  ![test](https://github.com/josesison1/JoseStoreSln/blob/master/Chapter%208%20Screenshot/Finalized%20Test%20Cases.PNG)

---
# Chapter 9
---
##  Checkout page Fig 9-4.
  ![checkout](https://github.com/josesison1/JoseStoreSln/blob/master/Chapter%209%20Screenshot/Checkout%20fig%209-4.PNG)
  ---
##  Fields error page Fig 9-5.
  ![error](https://github.com/josesison1/JoseStoreSln/blob/master/Chapter%209%20Screenshot/ErrorCheckOutMessage%20fig%209-5.PNG)
  ---
##  Ordered page Fig 9-6.
  ![ordered](https://github.com/josesison1/JoseStoreSln/blob/master/Chapter%209%20Screenshot/Ordered%20fig%209-6.PNG)
---
## Test Cases
  ![test](https://github.com/josesison1/JoseStoreSln/blob/master/Chapter%209%20Screenshot/test%20cases.PNG

