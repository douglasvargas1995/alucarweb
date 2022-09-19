<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

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


## Executar as migrations(Opcional)
$ php artisan migrate

## Gerar chave necessária para executar o sistema
$ php artisan key:generate

## Executar o sistema 
$ sudo php artisan serve

# Observações
Para acessar o sistema, utilize o caminho //localhost/alucar/public que apresenta uma opção de login ou um novo registro no canto superior direito da tela.

