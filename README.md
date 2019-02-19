# Manual Symfony 3.4


Para fazer o download do manual execute os seguintes comandos:

$ sudo git clone https://github.com/leonardofaria00/Manual-Symfony-3.4.git

$ cd Manual-Symfony-3.4/
$ vi README.md

    Baixando projeto Symfony
    $ sudo composer create-project symfony/framework-standard-edition symfony-project "3.4"
    
    Criando Banco de dados
    $ sudo bin/console doctrine:database:create
    
    Criando Entity
    $ sudo bin/console doctrine:generate:entity

    Gerar tabelas do banco de dados
    $ sudo bin/console doctrine:schema:create
    
    OBS: Para facilitar a vida, existe um comando que cria todo CRUD do projeto, mais
    é necessário existir a entidade criada.       
    Criando CRUD completo com View, Model, e Controller
    $ sudo bin/console generate:doctrine:crud
    
    
    Obs: depois de criar o crud do projeto, atualize seu banco de dados
    Atualizando o banco de dados:
    $ sudo bin/console doctrine:schema:update --complete
    $ sudo bin/console doctrine:schema:update --force
    
    








    
