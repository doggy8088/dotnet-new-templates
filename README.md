# .NET Core SDK 3.1

```sh
dotnet new -l --type=project --language=c# | wsl grep Web
```

```log
Templates                                         Short Name               Language      Tags
------------------------------------------------------------------------------------------------------------------------------
Worker Service                                    worker                   C#            Common/Worker/Web
Blazor Server App                                 blazorserver             C#            Web/Blazor
ASP.NET Core Empty                                web                      C#            Web/Empty
ASP.NET Core Web App (Model-View-Controller)      mvc                      C#            Web/MVC
ASP.NET Core Web App                              webapp                   C#            Web/MVC/Razor Pages
ASP.NET Core with Angular                         angular                  C#            Web/MVC/SPA
ASP.NET Core with React.js                        react                    C#            Web/MVC/SPA
ASP.NET Core with React.js and Redux              reactredux               C#            Web/MVC/SPA
Razor Class Library                               razorclasslib            C#            Web/Razor/Library/Razor Class Library
ASP.NET Core Web API                              webapi                   C#            Web/WebAPI
ASP.NET Core gRPC Service                         grpc                     C#            Web/gRPC
```

```sh
dotnet new worker -n worker
dotnet new blazorserver -n blazorserver
dotnet new web -n web
dotnet new mvc -n mvc
dotnet new webapp -n webapp
dotnet new angular -n angular
dotnet new react -n react
dotnet new reactredux -n reactredux
dotnet new razorclasslib -n razorclasslib
dotnet new webapi -n webapi
dotnet new grpc -n grpc
```
