# Laravel
Laravel Cheat Sheet


Create Project:
composer create-project laravel/laravel="5.2.*" php-todo

Start Project:
php artisan serve --port=8080

Change owner:
sudo chown -R $USER:$USER /opt/lampp/htdocs

Make project start:
composer install
composer update
composer dumpautoload

Make writeable:
chmod 777 bootstrap
chmod 777 vendor
chmod 777 storage


Create these folders in  storage/framework:
sessions
views
cache

How to run a specific seeder:
php artisan db:seed --class=UsersTableSeeder


How to run a seeder:
composer dump-autoload
php artisan db:seed
