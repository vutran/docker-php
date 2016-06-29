# Docker PHP

## Using Docker

*Build:*

````bash
$ docker build -t my-app-img .
````

*Run:*

`````bash
$ docker run -it --rm --name my-app -v "$PWD":/var/www/html -w /var/www/html my-app-img php index.php
`````

## Using Docker Composer

*Build:*

````bash
$ docker-compose build
````

*Run:*

````bash
$ docker-compose up
````
