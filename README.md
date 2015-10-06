# ExtJS 4 MVC Example - CRUD Grid with JSON, Ajax, PHP and MySQL

This is a real word example how to use a grid system with a real php/mysql server.
To serve php files I use rack-lagacy gem.

## Installation

Clone the repo.

Execute:

    $ bundle
    
Edit php/conectar.php file

    // php/conectar.php
    ...
    //nome do servidor (127.0.0.1)
    $servidor = "127.0.0.1";
 
    //usuário do banco de dados
    $user = "root";
 
    //senha do banco de dados
    $senha = "password";
 
    //nome da base de dados
    $db = "blog";
    ...

Create your database, in this example the name is blog:
    
    $ mysql -u root --password=password 
    
    mysql> CREATE DATABASE blog;

Populate your new database with fake data using sql/script.sql file.
    
    $ mysql -u root --password=password blog < sql/script.sql

## Usage

Execute:

    $ rackup
    
visit http://0.0.0.0:9292

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request



