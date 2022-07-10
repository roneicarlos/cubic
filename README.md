# Passo a passo

Crie o Arquivo .env

```sh
cp .env.example .env
```

Dê permissões necessárias para o diretório e seus arquivos

```sh
sudo chmod -R 755 ~/full/path/to/cubic/folder/
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
