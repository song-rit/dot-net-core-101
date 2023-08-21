# How to initial project

### API
### Way 1 - by use solution

sh ```
dotnet new sln -n HelloApiSolution
```

sh ```
dotnet new webapi -n HelloApi
```

sh ```
dotnet sln HelloApiSolution.sln add HelloApi/HelloApi.csproj
```

sh ```
cd HelloApi
dotnet restore
dotnet build
dotnet run
```

### Console
### Way 1 - by use solution

sh ```
dotnet new sln -n HelloConsoleSolution
```

sh ```
dotnet new console -n HelloConsole
```

sh ```
dotnet sln HelloConsoleSolution.sln add HelloConsole/HelloConsole.csproj
```

sh ```
cd HelloConsole
dotnet restore
dotnet build
dotnet run
```
