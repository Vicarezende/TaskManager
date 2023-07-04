# Task Manager API

Esta é uma API simples de gerenciamento de tarefas, construída com o framework Laravel.

## Demonstração

[![Demonstração da API](https://img.youtu.be/69j8mQZTO6E.jpg)](https://youtu.be/69j8mQZTO6E)


## Requisitos

Certifique-se de ter os seguintes requisitos instalados em seu ambiente de desenvolvimento:

- PHP >= 7.3
- Composer
- Banco de dados MySQL

## Instalação

1. Clone este repositório para o seu ambiente local:

   ```bash
   git clone https://github.com/seu-usuario/task-manager-api.git

## Instale as dependências do projeto:

    cd task-manager-api
    composer install

## Configure o arquivo '.env' com as informações do banco de dados:

    cp .env.example .env
    php artisan key:generate

Abra o arquivo .env e defina as seguintes variáveis:

DB_CONNECTION=mysql</br>
DB_HOST=127.0.0.1</br>
DB_PORT=3306</br>
DB_DATABASE=task_manager</br>
DB_USERNAME=seu-usuario</br>
DB_PASSWORD=sua-senha</br>

## Execute as migrações do banco de dados:

    php artisan migrate

## Inicie o servidor de desenvolvimento:

    php artisan serve

A API estará disponível em http://localhost:8000.

## Rotas
GET /api/tasks: Lista todas as tarefas.</br>
GET /api/tasks/{id}: Obtém os detalhes de uma tarefa específica.</br>
POST /api/tasks: Cria uma nova tarefa.</br>
PUT /api/tasks/{id}: Atualiza uma tarefa existente.</br>
DELETE /api/tasks/{id}: Exclui uma tarefa.</br>
Certifique-se de usar uma ferramenta adequada, como o Postman, para testar as rotas da API.

## Licença
Este projeto está licenciado sob a licença MIT.


    Lembre-se de personalizar as informações conforme necessário, como o link do repositório, os requisitos do seu ambiente e as instruções de instalação.
