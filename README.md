<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About the Project

The ideia is for create a application to add things you want to do, so you won't forget.

## Getting Started

Follow the next steps so you can run the project without any errors.

## Running the Project

1. Clone the repository using this command:

```terminal
git clone https://github.com/lukebarbosa/Laravel-todo-list.git
```

2. Access the project folder on your terminal:

```terminal
cd Laravel-todo-list
```

3. Run the command to install all dependencies with Composer.

```terminal
composer install
```

4. Copy the .env.example config to a new file called .env

```terminal
cp .env.example .env
```

5. Change the database environment variables on .env:

- **DB_DATABASE**: Database that you created for the project.
- **DB_USERNAME**: MySQL username.
- **DB_PASSWORD**: MySQL password.
 
6. Run the key generator on terminal

```terminal
php artisan key:generate
```    

7. Run the migrations on terminal

```terminal
php artisan migrate
```

8. Run the application

```terminal
php artisan serve
```
## THE END
