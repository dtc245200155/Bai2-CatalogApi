# Catalog API - Bai 2

RESTful API cho ung dung phan tan.

## Technologies
- ASP.NET Core Web API
- .NET 10
- C#

## Projects
- Catalog.Api: RESTful API
- Catalog.Client: HTTP Client

## Run
dotnet run --project src/Catalog.Api/Catalog.Api.csproj

## API Testing

### Start the API
dotnet run --project src/Catalog.Api/Catalog.Api.csproj

### Test endpoints
- GET / : Check API status
- GET /api/products : Get all products
- GET /api/products/1 : Get product by ID
- GET /api/products/999 : Test not found response
- POST /api/products : Create a new product

### HTTP requests
Use the requests.http file to send HTTP requests and verify API responses.

## Project Structure

- src/Catalog.Api: ASP.NET Core RESTful API.
- src/Catalog.Client: Console application for API requests.
- requests.http: HTTP requests for API testing.
- CatalogApi.slnx: Solution file.
