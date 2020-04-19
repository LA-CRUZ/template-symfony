# Install

change .env in env.local and change this.
```
DATABASE_URL=mysql://root:root@db/your_bd
```

```
cd my_project
cd docker-symfony
docker-compose up
```
in another tab of your console.
⚠ for use a PHP version of container.
```
docker-compose exec php /bin/sh
composer install
```
you'll find the symfony website in http://localhost:8888/
and phpmyadmin in http://localhost:8080/ 


it's ready 😀

for stop server :
```
docker-compose stop
```