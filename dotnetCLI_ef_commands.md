# Commands

### Add-Migration
      
      dotnet ef migrations add "MigrationName" -p src/demoProjects/rentACar/Persistence/Persistence.csproj -s src/demoProjects/rentACar/WebAPI/WebAPI.csproj

### Update-Database

      dotnet ef database update -p src/demoProjects/rentACar/Persistence/Persistence.csproj -s src/demoProjects/rentACar/WebAPI/WebAPI.csproj
