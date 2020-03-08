# Docker server
Docker server is a full development environment based on Docker.
### Software
Docker server uses:
* NGINX 
* PHP
* MySQL
* Redis 
* phpMyAdmin

### Installation
1 - Clone docker-server
```sh
$ git clone https://github.com/tariik/docker-server.git
```
2 - Enter the docker-server folder and rename env-example to .env.
```sh
$ cp env.example .env
```
3 - Run your containers:
```sh
$ docker-compose up -d
```
4 - Directory & File Structure 
Open ***.env*** file and set your app directory name in ***APP_NAME***
```
project
│
└─── docker-server
│   │   ........
└───  code
    │─── APP_NAME
    │   │ ─── public
                │ ─── index.php
```
### Todos
 - ......
 - .....
### CMD example
```sh
$ docker-compose exec app php artisan config:cache
```
```sh
$ docker-compose exec mysql bash
```
License
----

MIT


**Free Software!**
