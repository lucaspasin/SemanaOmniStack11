# SemanaOmniStack11
Projeto desenvolvido durante a 11ª semana omniStack da rocketSeat

Abrir Aplicação:

Caso seja a primeira vez que vai abrir, antes do npm/expo start é necessário um npm install para baixar o node_modules.

npm start dentro da pasta backend(servidor configurado para abrir na porta 3333)
  Para resetar o banco de dados: 
    Deletar o arquivo "db.sqlite" da pasta src/database/
    Rodar npx/yarn knex migration:latest

npm start dentro da pasta frontend(acessar localhost:3000 para visualizar)

expo start dentro da pasta mobile(caso não abra automaticamente, acessar localhost:19002)
