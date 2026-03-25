# TequilasRestaruant
C# E‑Commerce Web Application
A full-stack ASP.NET e‑commerce site with product management, login system, and basic purchasing workflow.

📖 Project Description
This project is a C# ASP.NET e‑commerce web application that demonstrates CRUD operations, user authentication, and a basic purchasing flow (products, ingredients, and orders).
It is built as part of the Tooele Tech C# E‑commerce Application course to practice real-world web development concepts including MVC structure, database integration, and session-based shopping carts.
​

⚙️ Setup Instructions
Prerequisites
Visual Studio (Community or higher) with ASP.NET and web development workload installed

SQL Server or SQL Express

.NET (version used in this project: <insert .NET / ASP.NET version here>)

1. Clone the Repository
bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
2. Configure the Database
Open the solution in Visual Studio.

Update the connection string in appsettings.json (or Web.config, depending on your project):

json
"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER;Database=YOUR_DB;Trusted_Connection=True;MultipleActiveResultSets=true"
}
Apply migrations or create the database:

Using EF Core:

Open Package Manager Console and run:

### powershell
## update-database
Or manually run the provided SQL script: Database/Script.sql (if you created one).

3. Run the Application
Set the main web project as Startup Project.

Press F5 or click Run in Visual Studio.

The application will start at https://localhost:xxxx or http://localhost:xxxx.

4. Test Login (if seeded)
Default admin:

Email: admin@example.com

Password: Admin@123

Default user:

Email: user@example.com

Password: User@123

(Update these to match your actual seeded data.)


🧠 Debugging & Development Notes
During development, the following debugging techniques were used (as recommended in the course):

Used breakpoints in Visual Studio to step through controller actions and check model values.

Read exception messages and stack traces to identify null references or SQL issues.

Inspected variables using the Locals and Watch windows to validate data coming from the database.

Isolated methods for CRUD operations and tested them individually before wiring them into the UI.

Consulted Microsoft Docs and online resources for ASP.NET, Entity Framework, and C# specific errors.


👤 Author
Name: Jesse Doake

Course: C# E‑commerce Application – Tooele Technical College

GitHub: https://github.com/valientjuno

