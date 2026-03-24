# Smart Inventory Management API

ASP.NET Core Web API for product/category/stock management using EF Core + SQLite.

## Setup

1. `dotnet restore`
2. `dotnet build`
3. `dotnet run`

## Endpoints

- `GET /api/categories`
- `GET /api/categories/{id}`
- `POST /api/categories`
- `PUT /api/categories/{id}`
- `DELETE /api/categories/{id}`

- `GET /api/products`
- `GET /api/products/{id}`
- `POST /api/products`
- `PUT /api/products/{id}`
- `DELETE /api/products/{id}`
- `PATCH /api/products/{id}/stock` (body: integer positive/negative)

## Database

- SQLite file: `inventory.db`
- Migrations folder: `Migrations`
