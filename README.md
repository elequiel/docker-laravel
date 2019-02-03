   ![back](https://user-images.githubusercontent.com/40737835/52116190-ad878380-25f7-11e9-820b-ddd5e0682433.png)

# Docker images to Laravel
A Docker PHP development environment.

## Usage
Run it in your terminal with docker-compose to up the components and start that
```
docker-compose up -d

docker-compose exec app php artisan key:generate
```
If everything is right, just access your localhost to see the welcome page from laravel.

http://localhost

## Components
* PHP: 7.2.4
* MySQL: 5.7
* Redis: 4.0
* Nginx: 7.2
