# Laravel Admin

Project of an Administrative Panel developed with the Laravel Framework 5.

## Features

- Auth
- ACL
- ORM
- Validator
- MultiLanguages
- Routes
- Artisan
- Grid View
- Pagination
- Export to Excel
- Flash Messages
- View Blade

## Tecnologies

- PHP 7
- JS
- Jquery
- CSS and SCSS
- Bootstrap
- Composer

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


## License

MIT
