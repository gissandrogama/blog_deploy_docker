# Startar a aplicação

- configurar p dev.exs com o seu banco de dados postgres

Startar a aplicação com o docker-compose

- você precisa configurar o dev.exs>hostname para **bd**

Startar a plicação em ambiente docker de produção
Obrigatorio passar como variaveis de ambientes: SECRET_KEY_BASE, DATABASE_URL

- docker build -t nomerepo/nomeprojeto:versao .
- docker run --env-file .env -p 8080:4000 nomerepo/nomeprojeto:versao
