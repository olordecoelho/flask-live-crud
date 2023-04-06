# Flask Live CRUD

Created by: Daniel Coelho
Created time: April 6, 2023 9:52 AM
Last edited by: Daniel Coelho
Last edited time: April 6, 2023 10:05 AM

O repositório Flask Live CRUD é uma aplicação de CRUD (Create, Read, Update, Delete) que roda em Docker com Flask. É possível clonar o repositório e executá-lo com apenas alguns comandos.

## Instalação

Para instalar e executar o Flask Live CRUD, siga os seguintes passos:

1. Clone o repositório do GitHub:

```
git clone <https://github.com/olordecoelho/flask-live-crud.git>

```

1. Entre na raiz do projeto:

```
cd flask-live-crud

```

1. Execute o seguinte comando para construir a imagem Docker:

```
docker compose build

```

1. Finalmente, execute o comando abaixo para iniciar o aplicativo:

```
docker compose up flask-live-crud

```

## Utilização

Após a execução dos comandos de instalação, o aplicativo estará rodando em [http://localhost:5000](http://localhost:5000/).

A página inicial exibirá uma lista de usuários pré-cadastrados, e você poderá navegar pelos links para adicionar, editar ou excluir usuários.

## Contribuição

Se você deseja contribuir para o desenvolvimento do Flask Live CRUD, sinta-se à vontade para fazer um fork do repositório e enviar suas alterações através de um pull request.
