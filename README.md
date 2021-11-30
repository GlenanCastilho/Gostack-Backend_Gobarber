<div align="center">
  <img src="https://user-images.githubusercontent.com/67304453/143960914-8ef99d4a-d363-49b5-ad03-177465bbcc50.png" width="300" >
</div>

##

<img src="https://user-images.githubusercontent.com/67304453/143960946-072c5f81-54a1-4c36-bbae-513307ef8334.png" width="1200"/>

<br>
<br>

<h1>📃 Sobre</h1>
 
<h4 align="justify">Uma aplicação feita para controlar a agenda dos prestadores de serviço, como Salões de Beleza e Barbeiros. Já os clientes podem fazer os agendamentos via aplicação Mobile.</h4>

<br>

<h1>🔧 Dependencias</h1>

<ul>
  <li>NodeJS</li>
  <li>express</li>
  <li>typescript</li>
  <li>typeorm</li>
  <li>postgres</li>
  <li>mongodb</li>
  <li>redis</li>
  <li>jest/ts-jest</li>
  <li>uuidv4</li>
  <li>date-fns</li>
  <li>multer</li>
  <li>celebrate/joi</li>
  <li>dotenv</li>
  <li>class-transformer</li>
  <li>rate-limiter-flexible</li>
  <li>Amazon SES</li>
  <li>Amazon S3</li>
</ul>

<br>

<h1>📚 Requisitos</h1>

<ul>
  <li>Git</li>
  <li>Docker</li>
  <li>Node.js</li>
 </ul>

   <br>
   
<h1>🚀 Iniciando o projeto</h1>

<h4>
  Criar container com instância do postgres:
  <br>
  $ docker run --name database -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres
  
  <br>
  <br>
  
  Criar container com instância do mongo:
  <br>
  $ docker run --name mongodb -p 27017:27017 -d -t mongo
  
  Criar  container com instância do redis:
  <br>
  $ docker run --name redis -p 6379:6379 -d -t redis:alpine
  
  Instalar as dependências:
  <br>
  $ yarn
  
  Executar as migrations:
  <br>
  $ yarn typeorm migration:run
  
  Rodar a aplicação:
  <br>
  $ yarn dev:server
</h4>
