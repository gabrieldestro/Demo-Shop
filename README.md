How to Debug?



Start the app

Execute the command to create the DB:
docker compose up -d





.NET Migrations:



dotnet ef migrations add InitialCreate -s API -p Infrastructure
dotnet ef migrations remove -s API -p Infrastructure
dotnet ef database update -s API -p Infrastructure





