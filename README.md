# Passo a passo

Crie o Arquivo .env

```sh
cp .env.example .env
```

Suba os containers do projeto

```sh
docker-compose up -d
```


Acessar o container

```sh
docker-compose exec app bash
```


Instalar as dependências do projeto

```sh
composer install
```

Gerar a key do projeto Laravel

```sh
php artisan key:generate
```

Acesse o projeto
[http://localhost:8000](http://localhost:8000)
