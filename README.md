# Nodejs-TDD-Jest
Teste de integração com backend Nodejs utilizando framework Jest 

## Crie a database
Rode o comando abaixo para criar a imagem docker do postegres na sua máquina:

``docker run --name <nome-da-database> -e POSTGRES_PASSWORD=<senha-de-conexao> -d -p 5432:5432 postgres`` 

## Configure o seu arquivo .env
Altere o arquivo .env.example para apenas .env

Insira suas credenciais de acesso:<br/>

> DB_HOST=localhost <br/>
> DB_USER=postgres <br/>
> DB_PASS=<senha-de-conexao> <br/>
> DB_NAME=postgres <br/>


## Instale as dependencias 
``yarn`` ou ``npm install`` 

## Rode o teste
``yarn test`` ou ``npm test``
