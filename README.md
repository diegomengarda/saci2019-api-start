# SACI 2019 - API Start
Repositório base para criamos nossa API com o Laravel


## Instruções de Instalação
```
git clone https://github.com/diegomengarda/saci2019-api-start.git

cd saci2019-api-start/

./composer.phar create-project --prefer-dist laravel/laravel api "5.8.*"

touch database/database.sqlite
```

## Criando o Model, Controller e Migration
```
php artisan make:model Student --migration

php artisan make:controller StudentController --api
```

## Rodando nossa migration
```
php artisan migrate
```

## Rodando nossa API
```
php artisan serve
```
