# Flask Live CRUD

Created by: Daniel Coelho

Uma aplicação de CRUD (Create, Read, Update, Delete) que roda em Docker com Flask.

## Instalação

Para instalar e executar o Flask Live CRUD, siga os seguintes passos:

1. Clone o repositório do GitHub:

```
git clone https://github.com/olordecoelho/flask-live-crud.git

```

1. Entre na raiz do projeto:

```
cd flask-live-crud

```


1. Execute o seguinte comando para iniciar um contêiner de banco de dados em segundo plano no Docker:

```
docker compose up -d flask_db

```

2. Execute o comando abaixo para construir as imagens dos serviços definidos no arquivo docker-compose.yml:

```
docker compose build

```
3. Execute o comando abaixo para iniciar um serviço específico, chamado "flask_app", definido no arquivo docker-compose.yml:

```
docker compose up flask_app

```

## Utilização

Após a execução dos comandos de instalação, o aplicativo estará rodando em http://localhost:4000 e o seu banco de dados em http://localhost:5432/.

Você poderá criar listas de usuários e também navegar pelos links para adicionar, editar ou excluir usuários.

## Contribuição

Se você deseja contribuir para o melhoramento do Flask Live CRUD, sinta-se à vontade para fazer um fork do repositório e enviar suas alterações através de um pull request.
