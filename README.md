# CrudWebAPI - New American Business Association #
## Author: John San Pietro ##

### Back End ###

### Objective: ###

Create a 3 tier(Full stack) application (SQL Database, C# .Net Web API, React Frontend) and deploy it to the Azure cloud and have all 3 tiers work together.


### Deployed: Azure Cloud: 
Links:<br>
	  - https://johnspreactfrontend.azurewebsites.net/  - Front End / <br>
	  - https://coolapi.azurewebsites.net/ - API / <br>
	  - https://cooldatabasedbserver.database.windows.net - Database
    
## Products: ## 

### - SQL Database ### 

### - .Net core WebApi ###


### Diagram: ###

![Diagram](https://github.com/88V/CrudWebAPI/blob/main/API.jpg)


## SQL Database ##

The database was generated using Entity Framework with a code first migration. This database was designed using the "People controller" class within the API project.
Functions: Create, Read, Update, Delete data within Person table with First Name and Last Name fields.
Connection string: "DefaultConnection" is stored in AppSettings.json inside the WebAPI project.
Hosted on Azure via "deploy" feature inside Visual Studio.

### Deployed: ### Azure Cloud: <br>  https://cooldatabasedbserver.database.windows.net

Learning sources:

Udemy Course : ".Net Web API & Entity Framework Crash course" https://www.udemy.com/course/aspnet-web-api-2-hands-on/


## .Net Core WebAPI ##

Built a new WebAPI project with scaffolding from Visual Studio . The API is controlled via a "People" controller which has various routes such as Get, Push, Put, and Delete to affect 2 fields, first and last name of a person. <br>

Using this controller, I performed an Entity Framework code first migration witht the following command: .net ef add new initialCreate. This created the database with the table "People" and colums of "First name" and "Last Name" and made the connection between the database and the web API.


### Deployed: ### Azure cloud https://coolapi.azurewebsites.net/

Functions: Route requests and data to and from the backend database to the client side application for interpretation and presentation to the user in a format consumable by React JS.

### Learning sources: ###

Udemy Course : ".Net Web API & Entity Framework Crash course" https://www.udemy.com/course/aspnet-web-api-2-hands-on/

### My Experience and challenges: ###

Prior to starting this project I have never worked with C# / .Net in any capacity, or even any sort of database. This was all new. I relentlessly youtubed and googled my way to completion. Seeing how things started to "talk" to each other was the most exciting part. The final icing on the cake was being able to see the project be deployed on the Azure cloud and work from anywhere across the internet. This project really highlighted the value of knowing full stack development.



