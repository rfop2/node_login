# node_login
Usando NodeJS com algumas bibliotecas eu criei umas telas simples de cadastro e registro num banco dedados na nuvem(mongoDB Atlas).
Nesse projeto tem o uso de mongoose, express, bcryptjs, passport, passport-local, ejs, express-ejs-layout, connect-flash.
Descompate o zip ou us git clone e abre ele com o VS Code.

Para rodar esse projeto:
1. Instale o NodeJS no pc.
2. Instale as bibliotecas necessárias usando o terminal dentro da pasta do projeto usando: 
npm i express bcryptjs passport passport-local ejs express-ejs-layouts mongoose connect-flash
3. Instale o nodemon usando: npm i -D nodemon
4. Rode o programa usando: npm run dev
5. Acesse localhost:5000


bcryptjs: para encriptar as senhas
passport passport-local: lida com login do usuario
ejs express-ejs-layout: lida com os layouts(interface)
monggose conecta o projeto ao mongoDB Atlas (um banco de dados na nuvem)
connect-flash: faz uns pop-out na interface
nodemon: roda o programa de forma mais imples

