# Lududs DB

Lududs DB is a web application that allows users to search for their favorite games and view screenshots and trailers. The application is built using Angular and Laravel, and it uses the RAWG API to retrieve game data.

## Features

- Search for games using the RAWG API
- View screenshots and trailers for games
- Register and login users

## Technologies

- Angular 15.2.3
- Laravel 9
- RAWG API

# Getting Started

To run Lududs DB locally, follow these steps:

## Clone the repository

Install dependencies for the Laravel backend:

<pre>composer install or composer update</pre>

Create a .env file from the .env.example file and add your database credentials

---

## Generate an application key:

<pre>php artisan key:generate</pre>

## Run database migrations:

<pre>
php artisan migrate
</pre>

## Install dependencies for the Angular frontend:

<pre>npm install</pre>

## Start the Laravel backend:

<pre>php artisan serve</pre>

## Start the Angular frontend:

<pre>ng serve</pre>

Navigate to http://localhost:4200 in your web browser to use Lududs DB.

Contributing
Contributions to Lududs DB are welcome! If you find a bug or have a feature request, please open an issue. If you want to contribute code, please fork the repository and create a pull request.


