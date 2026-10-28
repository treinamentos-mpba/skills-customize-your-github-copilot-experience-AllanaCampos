# 📘 Atividade: Building REST APIs with FastAPI

## 🎯 Objetivo

Construa uma API REST com FastAPI para praticar rotas HTTP, validação de dados com modelos Pydantic e respostas com status codes apropriados.

## 📝 Tarefas

### 🛠️ Criar a aplicação e uma rota de status

#### Descrição
Crie uma aplicação FastAPI e implemente uma rota simples para indicar que a API está funcionando.

#### Requisitos
O programa concluído deve:

- Criar uma instância da aplicação FastAPI em `main.py`.
- Implementar a rota `GET /health`.
- Retornar um objeto JSON com o status da aplicação, por exemplo `{"status": "ok"}`.
- Permitir iniciar a aplicação localmente com Uvicorn.

### 🛠️ Criar endpoints para uma coleção de tarefas

#### Descrição
Implemente endpoints para cadastrar e listar tarefas. Armazene os dados em memória; não é necessário configurar um banco de dados.

#### Requisitos
O programa concluído deve:

- Definir um modelo Pydantic para validar os dados de uma tarefa, incluindo uma descrição não vazia.
- Implementar `POST /tasks` para cadastrar uma tarefa e retornar o registro criado.
- Implementar `GET /tasks` para retornar todas as tarefas cadastradas.
- Atribuir um identificador único a cada tarefa criada.
- Retornar o status HTTP `201 Created` ao criar uma tarefa.

### 🛠️ Gerenciar tarefas por identificador

#### Descrição
Adicione operações para consultar, atualizar e remover uma tarefa específica usando seu identificador.

#### Requisitos
O programa concluído deve:

- Implementar `GET /tasks/{task_id}` para consultar uma tarefa.
- Implementar `PUT /tasks/{task_id}` para atualizar uma tarefa existente.
- Implementar `DELETE /tasks/{task_id}` para remover uma tarefa existente.
- Retornar o status HTTP `404 Not Found` quando o identificador não corresponder a uma tarefa.
- Retornar uma resposta de sucesso apropriada para cada operação concluída.