# blazorapp-webassembly-display-list

Blazor App

.NET 6

ASP.NET Core Blazor WebAssembly - Display a list of items / Users

# Creates a global json

dotnet new globaljson --sdk-version 6.0.320 --force

# Functionality of the Web App

- Display a Lit of Items as a SPA Demo

# Tech used for creating the Web App

- A Blazor Webassembly Web Client as a SPA 
- A traditional Webhotel for hosting
- VS Code

# Development

dotnet run

# Production

Create a self contained build for production at the remote server / traditionel web hotel

dotnet publish webapi.csproj --configuration Release --runtime win-x86 --self-contained

Upload the build to remote server

At my remote servers the web.config needs to be without the folowing:

hostingModel="inprocess"

# Usefull checklist for BlazorApp.csproj

- Sdk=Microsoft.NET.Sdk.BlazorWebAssembly
- RootNameSpace BlazorApp RootNameSpace 
