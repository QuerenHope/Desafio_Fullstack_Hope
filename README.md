## Cadastros de Clientes

Aplicação com o untuito de:

1º: Cadastrar um usúario;

2º: Ser possível o usuáro efetuar login no sistema;

3º: O usuário poderá cadastrar clientes, editá-los e excluí-los;

4º: Cadastrar contatos em cada cliente, editá-los e excluí-los;

Tecnologias utilizadas no projeto


Html5 css react Typescript material-ui express express


## Instruções para rodar o projeto com DOCKER 

- Dentro da pasta BACKEND-EXPRESS crie o arquivo .env conforme o .env.example: troque o "postgres_user" e o "postgress_password" do DATABASE_URL e as demais variáveis pelos seus dados.

DB_USER=

DB_PASSWORD=

DB_HOST=

DB=

SECRET_KEY=

DATABASE_URL="postgres://<user>:<password>@<host>:<port>/<db>"


- Na pasta raiz do projeto Fullstack, abra o terminal e execute o comando:
docker compose up

Acessse o Frontend pelo navegador
http://localhost:3000
