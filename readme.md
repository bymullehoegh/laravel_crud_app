<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

## CRUD in Laravel 5.8

Laravel CRUD application
Create, Read, Update, Delete application, made with laravel. 
Tutorial credit: http://bishrulhaq.com/posts/crud-in-laravel

        Run Compser Update
        Edit the .env file with relevant database credentials.
        Run 'php artisan migrate'
        Run php artisan serve
        Enter the http://127.0.0.1:8000/ in your browser

## Files: database file. 
            laravel_crud_sql inside the root folder.

## Errors: SQLSTATE[HY000] [2002] Connection refused
            Edit the config/database.php line 45 (under MYSQL) to this:
            'host' => env('DB_HOST', 'localhost'), instead of http://127.0.0.1
