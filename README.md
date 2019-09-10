# Prueba-renato

## Settings
To make run project follow those steps:
### 1. Create .env file(copy .env.example) and on DB_DATABASE="YourDB", create manually DB
### 2. composer install
### 3. php artisan migrate:refresh --seed (this runs migrations and seeders)
### 4. php artisan serve (serve project)

### Frontend is made with mdbootstrap cdn, if you are working locally you need to download mdbootstrap css,js, put it on public/css || public/js and route it on resources/views/layouts/app (//localhost:8000/css/mdbootstrap.min.css)
