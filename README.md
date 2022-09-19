# alucarweb
Projeto web para gerenciar o processo de alugueis de carros. Feito em php com laravel.

# Instalação das tecnologias utilizadas
## PHP
$ sudo apt install php php-xml php-pgsql

## Composer
$ sudo apt install composer

## Docker Compose(Opcional)
$ sudo apt install docker-compose

# Sistema
## Clone
$ git clone https://github.com/douglasvargas1995/alucarweb.git

## Depois de baixar o projeto, acesse a pasta e instale as dependências necessárias
$ composer install

Para acessar o banco, crie uma cópia do arquivo .env e configure a conexão.\
Utilizei migration para o banco de dados, mas caso seja necessário, o script com o sql está na pasta <i>database</i> e também estou anexando o arquivo no email.

## Criar e executar o banco pelo docker-compose(Opcional)
$ sudo docker-compose up -d

## Executar as migrations(Opcional)
$ php artisan migrate

## Gerar chave necessária para executar o sistema
$ php artisan key:generate

## Executar o sistema 
$ sudo php artisan serve
