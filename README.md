composer create-project laravel/laravel --prefer-dist laravel-crud-app
php artisan config:clear       //clean configuration cache
php artisan make:model Student -m
php artisan migrate
php artisan make:controller StudentController --resource
php artisan route:list

layout.blade.php
index.blade.php
create.blade.php
edit.blade.php

php artisan serve

http://127.0.0.1:8000/students/create
http://127.0.0.1:8000/students