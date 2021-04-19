<h1>Authentication with Laravel Breeze</h1>

<b>Note:</b>
<br />
We will use $ to describe the commands that will be used with regular user.

We will use # to describe the commands that will be used with superuser.

1) Run the following commands in sequence to deploy the project in a development environment:

$ composer install

$ npm install

$ npm run dev

2) Create and configure a database

$ php artisan migrate

$ php artisan db:seed

3) Next, you may navigate to your application's / login or / register URLs in your
web browser. All of Breeze's routes are defined within the routes / auth.php
file.

Based in the example -> https://laravel.com/docs/8.x/starter-kits#laravel-breeze