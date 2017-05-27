# CakePHP Docker Image

## Quick Start
```
$ git clone git@github.com:cakephp/app.git cakephp
$ cd cakephp
$ docker run -d -p 80:80 -p 443:443 -v ${PWD}:/var/www/cakephp --name cakephp shimomo/cakephp
$ docker exec -it cakephp composer install
```

## License
The CakePHP Docker Image is open source software licensed under the [MIT license](../LICENSE).
