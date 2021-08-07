# Accounts Payable Application
Team Project for Advanced .NET Programming. 

    Application that will have CRUD Functionality: 

    * Create
    * Retrieve
    * Update
    * Delete
    
## Prerequisite 

- [Visual Studio IDE](https://visualstudio.microsoft.com/)
- [Windows Forms App C# (.NET Framework)](https://docs.microsoft.com/en-us/visualstudio/ide/create-csharp-winform-visual-studio?view=vs-2019)
- [Entity Framework 6 (EF6)](https://docs.microsoft.com/en-us/ef/ef6/)


        
## Approaches to data-driven development

- Creating Entity Framework DbContext Class

        Steps:

        1.) Go to the Solution Explorer in Visual Studio
        2.) Rt click on the project (second item) in the solution explorer
        3.) Click on Add
        4.) Choose New Item
        5.) Left margin click on Data
        6.) Choose ADO.NET Entity Data Model
        7.) Add Entity Framework Model to the project

*This will help us manage the connection and queries that will be sent to the database.*

- Database First Approaches
    - Empty database: Design database with tools
    - Existing database: Use exisiting database
    - Not a common approach with .NET Core
- Code First
    - Track all database changes in source control
    - Empty Code First: Create C# classes and generate the database
    - Reverse Engineer: Turn exisitng database into C# classes
