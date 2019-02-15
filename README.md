# Manual Symfony 3.4


Para fazer o download do manual execute os seguintes comandos:

$ sudo git clone https://github.com/leonardofaria00/FerramentaDev.git
$ cd Manual-Symfony-3.4/


Criando as tabelas do banco de dados
$ bin/console doctrine:schema:create
Atualizando as tabelas do banco de dados
$ php bin/console doctrine:schema:update –force
Criando controller
$ bin/console generate:controller
Criando Entity
$ bin/console doctrine:generate:entity

# Configurações para ambiente de desenvolvimento PHP no Ubuntu

    Este script foi testado na distribuição do Ubuntu 18.04 LTS e na 18.10 LTS
    
    Para fazer o download do script e iniciar a instalação execute os seguintes comandos:
    
    $ sudo git clone https://github.com/leonardofaria00/FerramentaDev.git
    $ cd FerramentaDev/
    $ sudo chmod +x setup.sh
    $ sudo ./setup.sh

Arquivo Shell Script com instalações das principais ferramentas de Desenvolvimento PHP.
Repository for php development script improvement.
It has commands for installation of the following tools: 
openjdk-8-jdk, apache2, php, MySQL, Docker, Composer, Docker-compose, Git, Filezilla, Putty, WorkBench, Node.js, vim and NetBeans.
