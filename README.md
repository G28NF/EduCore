# Studium

API simples desenvolvida com Python e FastAPI para gerenciamento de alunos.

Os dados são armazenados em um arquivo JSON.

## Funcionalidades

* Cadastrar aluno
* Listar alunos
* Consultar aluno por ID
* Atualizar aluno
* Excluir aluno

## Dados do aluno

Cada aluno possui:

* ID
* Nome
* Matrícula
* Curso

## Rotas

```text id="7u2z5v"
GET    /alunos
GET    /alunos/{id}
POST   /alunos
PUT    /alunos/{id}
DELETE /alunos/{id}
```

## Estrutura do projeto

```text id="y42j9k"
studium-api/
├── main.py
├── alunos.json
├── requirements.txt
└── README.md
```

## Tecnologias

* Python
* FastAPI
* JSON

## Objetivo

Praticar a criação de uma API REST simples com Python e FastAPI, utilizando operações CRUD e armazenamento de dados em arquivo JSON.
