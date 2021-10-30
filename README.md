# .NET SDK 6.0

- 列出所有專案範本

    ```sh
    dotnet new -l --type=project
    ```

    ```log
    These templates matched your input: type='project'

    Template Name                                 Short Name           Language    Tags
    --------------------------------------------  -------------------  ----------  -------------------------------------
    ASP.NET Core Empty                            web                  [C#],F#     Web/Empty
    ASP.NET Core gRPC Service                     grpc                 [C#]        Web/gRPC
    ASP.NET Core Web API                          webapi               [C#],F#     Web/WebAPI
    ASP.NET Core Web App                          razor,webapp         [C#]        Web/MVC/Razor Pages
    ASP.NET Core Web App (Model-View-Controller)  mvc                  [C#],F#     Web/MVC
    ASP.NET Core with Angular                     angular              [C#]        Web/MVC/SPA
    ASP.NET Core with React.js                    react                [C#]        Web/MVC/SPA
    ASP.NET Core with React.js and Redux          reactredux           [C#]        Web/MVC/SPA
    Blazor Server App                             blazorserver         [C#]        Web/Blazor
    Blazor WebAssembly App                        blazorwasm           [C#]        Web/Blazor/WebAssembly/PWA
    Class Library                                 classlib             [C#],F#,VB  Common/Library
    Console App                                   console              [C#],F#,VB  Common/Console
    MSTest Test Project                           mstest               [C#],F#,VB  Test/MSTest
    NUnit 3 Test Project                          nunit                [C#],F#,VB  Test/NUnit
    Razor Class Library                           razorclasslib        [C#]        Web/Razor/Library/Razor Class Library
    Windows Forms App                             winforms             [C#],VB     Common/WinForms
    Windows Forms Class Library                   winformslib          [C#],VB     Common/WinForms
    Windows Forms Control Library                 winformscontrollib   [C#],VB     Common/WinForms
    Worker Service                                worker               [C#],F#     Common/Worker/Web
    WPF Application                               wpf                  [C#],VB     Common/WPF
    WPF Class library                             wpflib               [C#],VB     Common/WPF
    WPF Custom Control Library                    wpfcustomcontrollib  [C#],VB     Common/WPF
    WPF User Control Library                      wpfusercontrollib    [C#],VB     Common/WPF
    xUnit Test Project                            xunit                [C#],F#,VB  Test/xUnit
    ```

- 批次建立所有專案範本

    ```sh
    dotnet new web -n web1 -o web
    dotnet new grpc -n grpc1 -o grpc
    dotnet new webapi -n webapi1 -o webapi
    dotnet new razor -n razor1 -o razor
    dotnet new webapp -n webapp1 -o webapp
    dotnet new mvc -n mvc1 -o mvc
    dotnet new angular -n angular1 -o angular
    dotnet new react -n react1 -o react
    dotnet new reactredux -n reactredux1 -o reactredux
    dotnet new blazorserver -n blazorserver1 -o blazorserver
    dotnet new blazorwasm -n blazorwasm1 -o blazorwasm
    dotnet new classlib -n classlib1 -o classlib
    dotnet new console -n console1 -o console
    dotnet new mstest -n mstest1 -o mstest
    dotnet new nunit -n nunit1 -o nunit
    dotnet new razorclasslib -n razorclasslib1 -o razorclasslib
    dotnet new winforms -n winforms1 -o winforms
    dotnet new winformslib -n winformslib1 -o winformslib
    dotnet new winformscontrollib -n winformscontrollib1 -o winformscontrollib
    dotnet new worker -n worker1 -o worker
    dotnet new wpf -n wpf1 -o wpf
    dotnet new xunit -n xunit1 -o xunit
    ```

    > 注意：建立專案時若「預設命名空間」與「範本名稱相同」很容易遇到 NuGet 套件名稱衝突的錯誤。
