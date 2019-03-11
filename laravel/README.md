# Laravel Docker Image

## Quick Start
```
$ git clone git@github.com:laravel/laravel.git
$ cd laravel
$ docker run -d -p 80:80 -p 443:443 -v ${PWD}:/var/www/laravel --name laravel shimomo/laravel
$ docker exec -it laravel composer install
```

## License
The Laravel Docker Image is open source software licensed under the [MIT license](LICENSE).
