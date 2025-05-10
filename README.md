# ASP.NET MVC Movie Project
This readme provides an overview of the ASP.NET MVC Movie project created by EzequielTartaglia.
Overview
This is a web application built using ASP.NET MVC that allows users to browse, search, and manage a movie database. It demonstrates fundamental concepts of ASP.NET MVC architecture including models, views, controllers, data validation, and database integration.
Key Features

Movie Catalog: Browse a collection of movies with details like title, release date, genre, and price
Search Functionality: Filter movies by title or genre
CRUD Operations: Create, read, update, and delete movie entries
Data Validation: Form validation for movie submissions
Responsive UI: User-friendly interface adapting to different screen sizes

## Technology Stack

Framework: ASP.NET MVC
Language: C#
Database: Entity Framework with SQL Server
Front-end: HTML, CSS, JavaScript, Bootstrap
Authentication: ASP.NET Identity (if implemented)

## Installation and Setup

### Prerequisites:

Visual Studio (2019 or newer recommended)
.NET Framework or .NET Core (depending on the version)
SQL Server (LocalDB or full version)


### Clone the Repository:
git clone https://github.com/EzequielTartaglia/asp.net-mvc-movie.git

### Open the Project:

Open the solution file (.sln) in Visual Studio


### Database Setup:

Update the connection string in Web.config or appsettings.json
Run the database migrations in Package Manager Console:
Update-Database



### Run the Application:

Press F5 or click the "Run" button in Visual Studio



## Project Structure

Models: Defines the data structure for movies and other entities
Views: User interface templates
Controllers: Handle user requests and control application flow
Data: Database context and migrations
Content/wwwroot: Static files (CSS, JavaScript, images)

### Usage
After running the application:

Navigate to the Movies page to see the movie catalog
Use the search bar to filter movies
Click on details to see more information about a specific movie
Use Create, Edit, and Delete options to manage movie entries

### Learning Resources
This project demonstrates best practices for ASP.NET MVC development and can serve as a learning tool for:

### MVC architecture implementation
Entity Framework database operations
Form handling and validation
Routing in ASP.NET MVC

### License
This project is likely under an open-source license. Check the repository for specific license information.
