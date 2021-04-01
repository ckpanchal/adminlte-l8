## Install AdminLTE in laravel 8

Step 1: Clone repository using `git clone git@github.com:ckpanchal/adminlte-l8.git`

Step 2: Run `composer install` command to install all dependency packages

Step 3: Copy .env.example to .env using this command.
`cp .env.example .env`

Step 4: Setup database in .env file

Step 5: Run `php artisan migrate` to generate database tables from migrations

Step 5: Generate new key using this command
`php artisan key:generate`

Step 6: Finally start server
`php artisan serve`
