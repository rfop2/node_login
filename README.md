# node_login
Usando NodeJS com algumas bibliotecas eu criei umas telas simples de cadastro e registro num banco dedados na nuvem(mongoDB Atlas).
Nesse projeto tem o uso de mongoose, express, bcryptjs, passport, passport-local, ejs, express-ejs-layout, connect-flash.
O programa funciona localmente por isso é necessário entrar na conta do banco e colocar seu ip na whitelist.

Para rodar esse projeto:
1. Instale o NodeJS no pc
2. Acesse https://cloud.mongodb.com/user#/atlas/login e logue com a conta do banco de dados
3. Vá em Network Acess depois ADD IP ADRESS depois ADD CURRENT IP ADRESS e CONFIRM
4. Descompate o zip ou use git clone e abre ele com o Visual Studio Code
5. Abra um novo terminal
6. Instale as bibliotecas necessárias usando o terminal dentro da pasta do projeto usando: 
npm i express bcryptjs passport passport-local ejs express-ejs-layouts mongoose connect-flash
7. Instale o nodemon usando: npm i -D nodemon
8. Rode o programa usando: npm run dev
9. Acesse localhost:5000

Depois de registrar uma conta você pode fazer login e chegar ao dashboard, dar login em uma conta que não existe bloqueia o acesso. A senha tem que ter no minimo tamanho 6 e o email deve ter @. Todos os campos devem ser preenchidos para registrar uma conta.


bcryptjs: para encriptar as senhas
passport passport-local: lida com login do usuario
ejs express-ejs-layout: lida com os layouts(interface)
monggose conecta o projeto ao mongoDB Atlas (um banco de dados na nuvem)
connect-flash: faz uns pop-out na interface
nodemon: roda o programa de forma mais imples

