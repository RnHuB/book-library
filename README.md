# book-library
Book library in php using docker

#run command

$ docker build -t my-php-app .

$ docker run -it --rm --name my-running-app my-php-app

$ docker run -d -p 80:80 --name my-apache-php-app -v "$PWD":/var/www/html php:7.2-apache

then open your browser and open localhost:80
