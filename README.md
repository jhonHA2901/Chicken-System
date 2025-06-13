# Chicken-System API

This repository contains a basic Laravel setup for the Chicken-System project. It includes a minimal API for managing products.

## Getting Started

1. Install PHP 8.3 and Composer.
2. Run `composer install` inside the `chicken-system` directory.
3. Copy `.env.example` to `.env` and run `php artisan key:generate`.
4. Run migrations with `php artisan migrate`.
5. Start the development server using `php artisan serve`.

## Available API Routes

- `GET /api/products` — List all products
- `POST /api/products` — Create a new product
- `GET /api/products/{id}` — View a product
- `PUT/PATCH /api/products/{id}` — Update a product
- `DELETE /api/products/{id}` — Delete a product

Authentication is provided via Laravel Sanctum.
