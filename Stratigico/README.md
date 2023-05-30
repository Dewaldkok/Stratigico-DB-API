---> Stratigico DB API

        -->Scope

        The requirement is to setup a basic API that has the following:

        Database (code first)
        Create a database (locally) that has the following 2 tables:
        Login Table (Username and Password with basic encryption)
        User Details Table. Please populate with some basic details (name, surname, dob, etc)
        Please ensure that there is a relationship between the 2 tables.

        HTTP requests:

        Login/Authorization request. Should accept a username and password and return a security token as well as a success indicator (true/false).

        Get User Details request. Should accept the security token, and based on the username used in the Login/Authorization request return the details stored in the User Details Table. Additionally, this request should return the date difference between current date and DoB stored in the table (your choice of days/months/years). The return should contain the return object and a success indicator (true/false).

        Comments in your code would be appreciated.

---

        -->Installation

        You can start off by cloning the Repo to your Local Machine


        $ git clone https://github.com/Dewaldkok/Stratigico-DB-API.git
        $ cd the_project

---

        -->Usage

        To run the application it would as simple as pressing F5 on your keaybopard if you do make use of Visual Studio as your IDE or by running a debug.

---

        -->NuGet Packages
        To run this application, you need to have the following NuGet packages installed:

        -Microsoft.AspNetCore.Mvc: This package provides the MVC framework for building web applications with ASP.NET Core.
        -Microsoft.EntityFrameworkCore: This package is used for working with databases using Entity Framework Core.
        -Microsoft.EntityFrameworkCore.Sqlite: This package allows you to use SQLite as the database provider with Entity Framework Core.
        -Swashbuckle.AspNetCore: This package enables Swagger UI integration in ASP.NET Core applications for API documentation and testing.
