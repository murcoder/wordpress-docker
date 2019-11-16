# wordpress-docker

A clean and flexible docker environment for your wordpress project.

This configuration is using the following images from [DockerHub](https://hub.docker.com/):
* __Webserver__: php:7.2-apache
* __Database__: mysql + phpmyadmin
* __Cache__: redis
* __Debug__: xdebug

## Requirements
* __Wordpress project__: Use an existing wordpress instance or just download it [here](https://wordpress.org/download/).

## Quickstart
1. __Install__ [docker](https://docs.docker.com/install/)

2. __Clone__ _wordpress-docker_ into your project directory:
    * ```git clone https://github.com/murcoder/wordpress-docker.git```

3. __Build container__: Navigate into your project directory, build and start the docker container: 
    * ```docker-compose build```
    * ```docker-compose up -d```

5. __Ready!__ Visit localhost::8080 and follow the instructions


## Customize

It's quite easy to change the basic setup by accessing the dockerfile or the yml file:

* __app.dockerfile__: Change PHP Version, webserver and apt packages here.
* __mysql__: Check docker-compose.yml::mysql  

