# ASP.NET Core Web API
From https://docs.microsoft.com/en-us/learn/modules/build-web-api-aspnet-core

## Setup
* Create folder
* run `dotnet new webapi --no-https` in terminal --> Creates basic project without https
* `dotnet new gitignore` add gitignore with default values

## Build
* `dotnet build` 

## Run:
* `dotnet run` --> runs at http://localhost:5000

## HttpRepl
* for making HTTP requests to test ASP.NET Core web APIs
* installed with `dotnet tool install -g Microsoft.dotnet-httprepl`

### Usage
* `httprepl http://localhost:5000` --> Connect to web API
* `connect http://localhost:5000` --> command to set a directory structure based on an OpenAPI description
* show endpoints with `ls` and navigate with `cd`
* close with `exit`

#### GET
* Test get-endpoint with `get`

#### POST
* `post -c "{"name":"Hawaii", "isGlutenFree":false}"`

#### PUT
* `put 3 -c  "{"id": 3, "name":"Hawaiian", "isGlutenFree":false}"`

## Todo
- [x] Exercise - Create a web API project
- [x] ASP.NET Core Web API Controllers
- [x] Exercise - Add a data store
- [x] Exercise - Add a controller
- [x] CRUD actions in ASP.NET Core


