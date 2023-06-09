# CPH Capstone README
Most technologies used in this project are Microsoft based. Below you will find location to the current files and communication mediums.

# Nuget Packages
## API Documentation
To help with documenting the projects API a popular Nuget package has been installed - Swagger. Swagger automates the documentation process for API's. 
* API Doc URL: https://YOUR LOCAL HOST PATH/swagger/index.html
* [Swagger Documentation](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)

## Logging with Serilog
Serilog is a popular Nuget package that helps with the logging process. Serilog generates a new text file for each new day the applicaiton is used. 
* Log files are located in the _logs_ file in the root directory.
* [Serilog Documentation](https://github.com/serilog/serilog)

## D3 Chart Referrences
* [Line Chart, Percent Change](https://observablehq.com/@d3/change-line-chart)
* [Boston-Area Rent Changes](https://observablehq.com/@harrislapiroff/boston-area-rent-changes)
* [Plot](https://observablehq.com/collection/@observablehq/plot)
* [Plot-github](https://github.com/observablehq/plot#curves)

### Plot
* https://github.com/observablehq/plot


### Plot Cheat Sheets
* https://observablehq.com/collection/@observablehq/plot-cheatsheets
* https://raw.githubusercontent.com/observablehq/plot-cheatsheets/main/plot-cheatsheets.pdf

## Package Considerations
* [CSVHelper](https://github.com/JoshClose/CsvHelper)

# File Storage
* <a href="https://etsu365.sharepoint.com/:f:/s/MiniPublicHealth/Ei3dtt5JimNDjmsh_WfMtdUBhMsgdmyfq8t68mnmypQXQA?e=7NXbyk">OneDrive SharePoint</a> - This is the location of all the current a privous capstone documents. 
* <a href="">Lucid Charts</a> - used to show 
# C# async await
* [Async await](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/cancel-async-tasks-after-a-period-of-time)
* [Cancellation Tokens](https://docs.microsoft.com/en-us/dotnet/api/system.threading.cancellationtoken?redirectedfrom=MSDN&view=net-5.0)

# Chat
* <a href="https://teams.microsoft.com/l/channel/19%3a003bad19bc74453f9af3ac02ca464f49%40thread.skype/General?groupId=8ef819a1-36fd-49ba-bbad-dff7ce480ebb&tenantId=962441d5-5055-4349-bad3-baec43c3d741">Microsoft Teams</a> - Here capstone participents can also access the OneDrive files and communicate with there teammembers. 

# Backlog Management
* <a href="https://cph-capstone.atlassian.net/jira/software/projects/CPH/boards/1/roadmap?assignee=unassigned&shared=&atlOrigin=eyJpIjoiODUzMzZmZTBkYjc3NDQ4NWI2MzhjNTBhYTI0ZmM1M2MiLCJwIjoiaiJ9">Jira</a> - This is a web based tool that will help the team keep track of the backlog and assign people to that backlog. The main issue with using Jira is that the HLR ID's don't transfer correctly. 
* 

# CPH Data
* <a href="https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation">County Health Rankings</a> - the location of where the yearly CSVs are published.

# Development Resources
* <a href="https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation">D3</a> - the JavaScript library that manipulates SVG paths in the browser to display visually appealing graphs and charts.
*  ASP.NET - Server-side development in an MVC patteren. 
*  JavaScript - used for frontend DOM manipulation
   *  [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch#supplying_request_options) - submitting a form using fetch api.
   *  [ECMAScript Standards pdf](https://www.ecma-international.org/wp-content/uploads/ECMA-262_12th_edition_june_2021.pdf)
   *  [ECMAScript Standards Website Doc](https://tc39.es/ecma262/)
*  Commenting with JavaScript Intellisense
   *  [Intellisense Docs](https://docs.microsoft.com/en-us/office/dev/add-ins/develop/get-javascript-intellisense-in-visual-studio)
*  Creating Roles: https://youtu.be/TuJd2Ez9i3I
*  UserManager (adding users to roles): https://docs.microsoft.com/en-us/dotnet/api/microsoft.aspnetcore.identity.usermanager-1?view=aspnetcore-5.0
*  Adding Properties to AspNetUser: https://www.youtube.com/watch?v=NV734cJdZts
*  Seeding the db: https://jorgeramon.me/2015/how-to-seed-users-and-roles-in-an-asp-net-mvc-application/, http://www.binaryintellect.net/articles/5e180dfa-4438-45d8-ac78-c7cc11735791.aspx, https://docs.microsoft.com/en-us/ef/core/modeling/data-seeding
*  Logging: https://docs.microsoft.com/en-us/aspnet/core/fundamentals/logging/?view=aspnetcore-5.0
*  Twitter Boot Strap v4.6.x: https://getbootstrap.com/docs/4.6/getting-started/introduction/
*  jQuery: https://jquery.com/ - NEED TO PHASE OUT WHEN REFACTORING


## Vuejs.org
Vuejs is growing in popularity and jQuery is not. Vue isn't an "exact" replacement of jQuery because a lot of the functionality that used to be inportant is now baked into vinilia JavaScript. 
https://vuejs.org/v2/guide/installation.html

# Considerations for Future Iterations

## Interactive US Map (Future iterations of CPH)
* <a href="https://www.google.com/maps/d/embed?mid=1LR2u1mms4-Nv8RlIVhvRZBcm8Q0&msa=0&ll=45.26966855666981%2C-122.70965409228255&spn=1.179884%2C2.469177&output=embed&z=9">Google Map Outline Example</a>
* <a href="https://youtu.be/cwpmvI4vxNQ">Google Maps Datalayer</a>
* GeoJson Map: https://geojson.io/#map=7/34.235/-113.049
* <a href="https://public.opendatasoft.com/explore/dataset/us-county-boundaries/table/?disjunctive.statefp&disjunctive.countyfp&disjunctive.name&disjunctive.namelsad&disjunctive.stusab&disjunctive.state_name&dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6InVzLWNvdW50eS1ib3VuZGFyaWVzIiwib3B0aW9ucyI6eyJkaXNqdW5jdGl2ZS5zdGF0ZWZwIjp0cnVlLCJkaXNqdW5jdGl2ZS5jb3VudHlmcCI6dHJ1ZSwiZGlzanVuY3RpdmUubmFtZSI6dHJ1ZSwiZGlzanVuY3RpdmUubmFtZWxzYWQiOnRydWUsImRpc2p1bmN0aXZlLnN0dXNhYiI6dHJ1ZSwiZGlzanVuY3RpdmUuc3RhdGVfbmFtZSI6dHJ1ZX19LCJjaGFydHMiOlt7ImFsaWduTW9udGgiOnRydWUsInR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJhbGFuZCIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiNGRjUxNUEifV0sInhBeGlzIjoic3RhdGVmcCIsIm1heHBvaW50cyI6NTAsInNvcnQiOiIifV0sInRpbWVzY2FsZSI6IiIsImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWV9&location=5,34.92197,-79.56299&basemap=jawg.streets">County Dataset</a>
* State GeoJson: https://eric.clst.org/tech/usgeojson/

## Display Directory CSVs on Upload Page
* MAKE MORE NOTES HERE.

# Direct links to County Health Ranking CSVs
* "https://www.countyhealthrankings.org/sites/default/files/analytic_data2019.csv"
* "https://www.countyhealthrankings.org/sites/default/files/analytic_data2018_0.csv"
* "https://www.countyhealthrankings.org/sites/default/files/analytic_data2017.csv"
* "https://www.countyhealthrankings.org/sites/default/files/analytic_data2016.csv"
* "https://www.countyhealthrankings.org/sites/default/files/analytic_data2015.csv"
* "https://www.countyhealthrankings.org/sites/default/files/analytic_data2014.csv"
* "https://www.countyhealthrankings.org/sites/default/files/analytic_data2013.csv"
* "https://www.countyhealthrankings.org/sites/default/files/analytic_data2012.csv"
* "https://www.countyhealthrankings.org/sites/default/files/analytic_data2011.csv"
* "https://www.countyhealthrankings.org/sites/default/files/analytic_data2010.csv"
