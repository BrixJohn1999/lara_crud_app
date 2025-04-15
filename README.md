## CREATING NEW LARAVEL PROJECT

`Composer create-project laravel/laravel lara-crud-app`

## composer require laravel/breeze

`php artisan breeze:install`

## CREATING TABLE

`php artisan make:migration create_blogs_table`

## CREATING MODEL

`php artisan make:mode Blog`

## CREATING CONTROLLER

`php artisan make:controller BlogController --resource`

## List all routes GET/POST/PUT

`php artisan route:list`

## add public asset to public folder

`php artisan storage:link`

## TO FIX No Application Encryption Key Has Been Specified

`php artisan key:generate`

## after cloning to create vendor folder

`composer install`
