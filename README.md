# Docker-Laravel
Deploy Laravel from Docker (php7.4 / mysql8 / nginx1.19)

# How To Use
## 1.Deploy
docker-compose up -d

## 2.make project
docker exec -ti laravel_php bash
composer create-project "laravel/laravel=6.*" sampleproject

## 3.setting change mode
cd sampleproject
chmod -R 777 storage
chmod -R 777 bootstrap/cache

## 4.start-up server
php artisan serve



