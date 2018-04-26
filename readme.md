# Laravel Admin

Project of an Administrative Panel developed with the Laravel Framework 5.

## Features

- Auth
- ACL
- ORM
- Validator
- MultiLanguages
- Routes
- Grid View
- Pagination
- Export to Excel
- Flash Messages
- View Blade

## Tecnologies

- PHP 7
- JS
- Jquery
- Json
- CSS and SCSS
- Bootstrap
- Composer
- Artisan

## Installation

```shell

$ git clone https://github.com/danilomeneghel/laravel_admin.git

$ cd laravel-admin.org

$ composer install -vvv

```

Then create a database with name `laravel_admin_demo` in your mysql. You can find database dump in `storage/mysql_dump/laravel_admin_demo.sql`,  import it:

```sql

$ mysql -u <your user> -p <your password>

mysql> create database `laravel_admin_demo`;

mysql> use `laravel_admin_demo`;

mysql> source storage/mysql_dump/laravel_admin_demo.sql

```

Back to terminal and start the web server:

```shell

$ php artisan serve

```

Finally open `http://localhost:8000/` in your browser.

## Connection

To be able to connect, I advise you to create an account on the panel.

  - You can use the default:
    User: admin
    Password: admin

## License

Laravel Admin is licensed under <a href="license.md">The MIT License (MIT)</a>.

## Screenshots

<img src="public/img/screenshot01.png"><br>
<img src="public/img/screenshot02.png"><br>
<img src="public/img/screenshot03.png"><br>
<img src="public/img/screenshot04.png"><br>
<img src="public/img/screenshot05.png"><br>
