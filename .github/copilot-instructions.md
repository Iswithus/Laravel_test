# GitHub Copilot Instructions

## Project Overview
This is a **Laravel 10** web application project.

## Tech Stack
- **Backend**: PHP 8.1+, Laravel 10
- **Authentication**: Laravel Sanctum (API tokens)
- **Frontend**: Blade templates, Vite
- **Database**: MySQL
- **Testing**: PHPUnit 10

## Project Structure
- `app/` – Application code (Models, Controllers, Middleware, Providers)
- `routes/` – Route definitions (`web.php`, `api.php`)
- `resources/views/` – Blade templates
- `database/` – Migrations, seeders, factories
- `tests/` – PHPUnit feature and unit tests
- `config/` – Laravel configuration files

## Coding Conventions
- Follow PSR-12 coding standards
- Use Laravel Eloquent ORM for database interactions
- Use Laravel's built-in helpers and facades
- Write PHPUnit tests for new features (place in `tests/Feature/` or `tests/Unit/`)
- Use `php artisan make:*` commands to scaffold new components

## Common Commands
```bash
php artisan serve          # Start development server
php artisan migrate        # Run database migrations
php artisan test           # Run tests
composer install           # Install PHP dependencies
npm install && npm run dev # Install and build frontend assets
```
