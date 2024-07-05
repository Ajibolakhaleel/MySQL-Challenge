📊 MySQL Challenges
Tasks:
Develop the database using MySQL (apply all the necessary table constraints and relationships).
Populate the database based on the data provided in the shared documents.
Develop Database Queries, Views, Functions, Procedures, and Triggers.
Deliverables:
SQL scripts for the database, all queries, functions, views, and stored procedures.
Diagrams illustrating database schema and relationships.
📁 Database
📅 Queries
Find all projects with a deadline before December 1st, 2024.
List all projects for "Big Retail Inc." ordered by deadline.
Find the team lead for the "Mobile App for Learning" project.
Find projects containing "Management" in the name.
Count the number of projects assigned to David Lee.
Find the total number of employees working on each project.
Find all clients with projects having a deadline after October 31st, 2024.
List employees who are not currently team leads on any project.
Combine a list of projects with deadlines before December 1st and another list with "Management" in the project name.
Display a message indicating if a project is overdue (deadline passed).
👁️ Views
Create a view to simplify retrieving client contact information.
Create a view to show only ongoing projects (not yet completed).
Create a view to display project information along with assigned team leads.
Create a view to show project names and client contact information for projects with a deadline in November 2024.
Create a view to display the total number of projects assigned to each employee.
Create a view to display project details along with the total number of team members assigned.
Create a view to show overdue projects with the number of days overdue.
🛠️ Functions
Create a function to calculate the number of days remaining until a project deadline.
Create a function to calculate the number of days a project is overdue.
🚀 Stored Procedures
Create a stored procedure to add a new client and their first project in one call.
Create a stored procedure to move completed projects (past deadlines) to an archive table.
Create a stored procedure to update project team members (remove existing, add new ones).
🔄 Triggers
Create a trigger to log any updates made to project records in a separate table for auditing purposes.
Create a trigger to ensure a team lead assigned to a project is a valid employee.
Create a trigger to prevent deleting a project that still has assigned team members.
🚀 Getting Started
To run these SQL scripts, ensure you have a MySQL environment set up. Import the provided scripts and execute them in your MySQL client.