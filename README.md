# ToDo Laravel App

Simple ToDo app with:

- Users
- Workspaces
- Notes
- API for external integrations

## Setup

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm install && npm run build
php artisan serve
```
