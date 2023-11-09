# LAMP stack for laravel 10 / Latest

*Spesification :*
- Linux Debian 10 (Buster)
- Apache 2
- PHP 8.2/latest
- Mariadb 10/latest
- Redis 7.2/latest
- Laravel 10/latest

### Beberapa file yang perlu dikonfigurasi :
*Some files need to be configured :*

1. config/php/php.ini
2. config/pma/config.inc.php
3. config/ssl/
4. config/vhosts/default.conf
5. www/(your exciting application files just put down here)

### Menjalankan aplikasi laravel
*How to run laravel app*

**- with apache2 and php-fpm**
1. run docker-compose
   > `docker-compose up -d`
2. open browser and type the url addres : http://localhost:80/public/html

**- with laravel artisan**
1. go to directory www
     `cd www`
2. run app
     `php artisan serve`
     or
     `php artisan serve --port 80`
3. open browser and type the url addres : http://localhost or http://localhost:80

That's it! & Good luck!
by [mazjohn.com](https://mazjohn.com)