# .NET Microservices

https://github.com/binarythistle/S04E03---.NET-Microservices-Course-

## Project setup
```
dotnet new webapi -n PlaformService
dotnet add PlatformService package AutoMapper.Extensions.Microsoft.DependencyInjection
dotnet add PlatformService package Microsoft.EntityFrameworkCore
dotnet add PlatformService package Microsoft.EntityFrameworkCore.Design
dotnet add PlatformService package Microsoft.EntityFrameworkCore.InMemory
dotnet add PlatformService package Microsoft.EntityFrameworkCore.SqlServer
```

## Project run
```
dotnet build
dotnet run
```

## Docker
```
docker build -t binaryhistle/platformservice . 
docker run -p 8080:80 -d binaryhistle/platformservice
```






