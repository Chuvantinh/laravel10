# laravel10 vs PHP Apache MongoDB Docker Composer

# How to run command of composer , php in docker
https://devops.tutorials24x7.com/blog/containerize-laravel-with-apache-mysql-and-mongodb-using-docker-containers

## Migration Command
docker-compose exec <php service name> php artisan migrate


Example: 
docker-compose exec php ls -l
docker-compose exec php php artisan migrate
Install package for connection betweenn laravel and mongodb:
docker-compose exec composer composer require mongodb/laravel-mongodb