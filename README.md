clone/download this project
cd to project folder
run composer install to install composer dependency
run npm install to install npm dependency
run npm run dev to compile assets (Mix)
copy .env.example to .env, and change the configuration as your machine.
run php artisan key:generate (if there is no key yet)
run your server, and create database (name same as in .env)
run php artisan migrate
run php artisan db:seed to seed the database with initial data
run your app directly or with php artisan ser
