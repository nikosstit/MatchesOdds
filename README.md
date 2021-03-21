# Matches And Odds Appi

This Api use .net core 3.1.

## Installation
Check into the appsettings.json the DefaultConnection
 (localdb) SQL SERVER:
 ```bash
 "Server=(localdb)\\mssqllocaldb;Database=aspnet-MatchesDB-7BE9FC14-E3E1-4D30-B471-E5414EE5E2FD;Trusted_Connection=True;MultipleActiveResultSets=true"
 ```
 OR IF YOU HAVE SQL SERVER NEED THIS:
```bash
 "DefaultConnection": "Data Source=.;Initial Catalog=MatchesDB;Integrated Security=True"
 ```
Use the migration commands 

```bash
* Add-Migration Initial
* Update-Database
```
Or Check This Link
*https://www.entityframeworktutorial.net/efcore/entity-framework-core-migration.aspx
## Run from POSTMAN
VERBS:
* Get: https://localhost:44382/api/matches
* Get: https://localhost:44382/api/matches/1
* Post: https://localhost:44382/api/matces
* Put: https://localhost:44382/api/matches/1
* Delete: https://localhost:44382/api/matches/1

check Resources Folder 

## Run from SWAGGER 

## Usage
Manage all Matches and Odds 

## Contributing

Please make sure run Update-Database. 
And check throw  VS the SQL Server Object Explorer Database.
If can not find go to menu->View and choose SQL Server Object Explorer.

##Nuget Packages
```bash
* Microsoft.EntityFrameworkCore.SqlServer v3.1.1
* Microsoft.EntityFrameworkCore.Tools v3.1.1
* Newtonsoft.Json v12.03
* Swashbuckle.AspNetCore v6.1.1
```

## License

