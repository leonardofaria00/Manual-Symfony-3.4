# Manual Symfony 3.4


Para fazer o download do manual execute os seguintes comandos:

$ sudo git clone https://github.com/leonardofaria00/FerramentaDev.git
$ cd Manual-Symfony-3.4/
$ vi README.md

    Baixando projeto Symfony
    $ composer create-project symfony/website-skeleton my-project
    
    Criando Banco de dados
    $ bin/console doctrine:database:create
    
    Criando Entity
    $ bin/console doctrine:generate:entity

    Gerar tabelas do banco de dados
    $ bin/console doctrine:schema:create
    
    OBS: Para facilitar a vida, existe um comando que cria todo CRUD do projeto, mais
    é necessário existir a entidade criada.       
    Criando CRUD completo com View, Model, e Controller
    $ bin/console generate:doctrine:crud
    
    
    Obs: depois de criar o crud do projeto, atualize seu banco de dados
    Atualizando o banco de dados:
    $ bin/console doctrine:schema:update --complete
    $ bin/console doctrine:schema:update --force
    
    








    
