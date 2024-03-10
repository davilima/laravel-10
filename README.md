
# Docker Com Laravel 10 e PHP 8.1

Suba os containers do projeto
```sh
docker-compose up -d
```


Acesse o container app
```sh
docker-compose exec app bash
```


Instale as dependências do projeto
```sh
composer install
```


Gere a key do projeto Laravel
```sh
php artisan key:generate
```

Acesse o projeto
[http://localhost:8989](http://localhost:8989)