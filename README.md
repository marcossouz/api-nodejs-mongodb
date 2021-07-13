# Construindo uma API com Node.js

Um projeto chamado Mentions. A Mentions existe para salvarmos pérolas (coisas engraçadas) que nossos amigos e amigas dizem durante o dia. Por isso precisaremos armazenar em um banco de dados o nome e frase que essa pessoa falou para depois listarmos isso em uma página web.

Para isso iremos utilizar Node.js, Express e MongoDB (um banco de dados). Inicialmente vamos desenvolver a função de criação, listagem, atualização e deleção de menções. Depois iremos trabalhar tratamentos de erros, autenticação, etc.

# Conteúdo

- [x] Parte 1: criando e listando dados
  - [x]  O projeto
  - [x]  Inicializando o projeto
  - [x]  Criando o servidor
  - [x]  Conectando ao MongoDB
  - [x]  Modelando nosso banco de dados
  - [x]  Criando os métodos de criar e listar dados do banco
  - [x]  Utilizando o Postman
  - [x]  Conclusão
- [ ] Parte 2: melhorando nossa criação e listagem de dados
  - [x] Retornando somente os dados que desejamos exibir
  - [x] Melhorando nossa organização de código com repository pattern
  - [ ] Validando entradas de dados
  - [ ] Conclusão

# Tecnologias

- Nodejs
- Express
- Mongodb (mongo atlas - https://cloud.mongodb.com/)

# Como executar o projeto

- adicionar o arquivo `.env`
  - adicionar dentro de `.env`: `DATABASE_CONNECTION_STRING=<your connection string>`
- executar `$ npm install`
- npm run dev


# Prints
#### Mongoatlas

![](https://i.imgur.com/IISIs2t.png)


#### Documentação

- https://documenter.getpostman.com/view/12239081/Tzm9hu2p


# Referências

- https://woliveiras.com.br/posts/construindo-uma-api-com-node-js-parte-1-criando-e-listando-dados/
- https://woliveiras.com.br/posts/construindo-uma-api-com-node-js-parte-2-melhorando-nossa-cria%C3%A7%C3%A3o-e-listagem-de-dados/
- https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/infrastructure-persistence-layer-design
- https://express-validator.github.io/docs/
