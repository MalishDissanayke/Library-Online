1)composer install

2) cp -r .env.example .env

3)config DB

    DB_CONNECTION=mysql

    DB_HOST=127.0.0.1

    DB_PORT=3306

    DB_DATABASE=laravel

    DB_USERNAME= root 

    DB_PASSWORD=
    
4)  php artisan key:generate
5)  php artisan migrate
6)  php artisan serve
7)  http://127.0.0.1:8000
