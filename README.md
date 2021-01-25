
Tutorial: Create a Web API with ASP.NET Core
https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio

To test the API, you can follow the Tutorial from the link above from the 'Install Postman'.
Basicaly, the routes are;
https://localhost:<port>/api/TodoItems -> TO GET ALL
https://localhost:<port>/api/TodoItems/{id} -> TO GET BY ID

NOTE: This example uses an in-memory database that must be started every time the application is started. There must be an item in the database before you can make a PUT call.
------------------------

#tips
If you want to add Authentication to your API, just access the same link from the Tutorial above and go to the 'Call the Web API with JavaScript' section;
https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio#add-authentication-support-to-a-web-api-21

if you want to call the API from a frontend, access the link;
https://docs.microsoft.com/en-us/aspnet/core/tutorials/web-api-javascript?view=aspnetcore-5.0