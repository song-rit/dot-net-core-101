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
cd hello-api
dotnet restore
dotnet build
dotnet run
```

