
Tutorial: Create a Web API with ASP.NET Core
https://docs.microsoft.com/pt-br/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio

To test the API, you can follow the Tutorial from the link above from the 'Install Postman'.
Basicaly, the routes are;
https://localhost:<port>/api/TodoItems -> TO GET ALL
https://localhost:<port>/api/TodoItems/{id} -> TO GET BY ID

NOTE: This example uses an in-memory database that must be started every time the application is started. There must be an item in the database before you can make a PUT call.