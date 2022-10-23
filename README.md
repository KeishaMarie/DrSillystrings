# Engineers and Machines Tracker

#### By Keisha Hepner

#### MVC Application to track Engineers and Machines

## Technologies Used

* C#
* HTML
* .NET 5
* Entity
* Asp.Net Core MVC
* MySql
* JavaScript

## This is an MVC application which allows a user to track Engineers and Machines using a many-to-many relationship. You are able to add Engineers and Machines individually, assign engineers to repair specific machines and edit details on both engineers and machines including delete and reassignment. 


## Setup/Installation Requirements

* Clone repository using url https://github.com/KeishaMarie/DrSillystrings
* Run dotnet build to build the application
* You will need to create a file in the project directory titled appsettings.json and insert the code below:
* {
"ConnectionStrings": {
"DefaultConnection": "Server=localhost;Port=3306;database=database;uid=YOURUSERNAME;pwd=YOURPASSWORD;"
}
}
* Be sure to tailor the database, username and password sections to your database, username and password
* Run dotnet restore then dotnet build to ensure everything is up to date.
* Install "dotnet ef tool" by running this command in your terminal: dotnet tool install --global dotnet-ef --version 5.0.1
* Create a Migration for your database by running this command in your terminal: dotnet ef migrations Initial
* Update your database by running this command in your terminal: dotnet ef database update
* Run dotnet run to run the application

## Known Bugs
* Header and Footer do not scale properly yet


## Copyright (c) <2022 Keisha Hepner>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

