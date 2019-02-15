# Manual Symfony 3.4


Para fazer o download do manual execute os seguintes comandos:

$ sudo git clone https://github.com/leonardofaria00/FerramentaDev.git
$ cd Manual-Symfony-3.4/
$ vi README.md


    Criando Banco de dados
    $ bin/console doctrine:database:create
    
    Criando Entity
    $ bin/console doctrine:generate:entity

    Criando as tabelas do banco de dados
    $ bin/console doctrine:schema:create
    
    Atualizando as tabelas do banco de dados
    $ php bin/console doctrine:schema:update –force
    
    Criando controller
    $ bin/console generate:controller
    
    OBS: Para facilitar a vida, existe um comando que cria todo CRUD do projeto, mais é necessário existir a entidade criada. Para isso execute o comando:
    
    Baixando projeto Symfony
    $ composer create-project symfony/website-skeleton my-project
    
    Criando Entidade
    $ bin/console doctrine:generate:entity
    
    Criando CRUD completo com View, Model, e Controller
    $ bin/console generate:doctrine:crud
    
    Atualizando o banco de dados
    $ bin/console doctrine:schema:update --complete
    $ bin/console doctrine:schema:update --force
    
    








    
