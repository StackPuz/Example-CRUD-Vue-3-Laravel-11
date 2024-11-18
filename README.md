# Example-CRUD-Vue-3-Laravel-11
- The example shows how to Building a Vue CRUD App with a Laravel API and using MySQL as a database.
- The article of this repository https://blog.stackpuz.com/building-a-vue-crud-app-with-a-laravel-api
- To find more resources, please visit https://stackpuz.com

## Prerequisites
- Node.js
- Composer
- PHP 8.2
- MySQL

## Installation
- Clone this repository `git clone https://github.com/stackpuz/Example-CRUD-Vue-3-Laravel-11 .`
- Change directory to Vue project. `cd view`
- Install the Vue dependencies. `npm install`
- Change directory to Laravel project. `cd ../api`
- Install the Laravel dependencies. `composer install`
- Create a new database and run [/database.sql](/database.sql) script to create tables and import data.
- Edit the database configuration in [/api/.env](/api/.env) file.

## Run project

- Run Vue project. `npm run dev`
- Run Laravel project `php artisan serve`
- Navigate to http://localhost:5173