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

2. What is a Connection String?

3. What is a Database Context?

4. What is a Model Repository?

5. Migration vs Scaffolding?
  
