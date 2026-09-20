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

```text
GET    /alunos
GET    /alunos/{id}
POST   /alunos
PUT    /alunos/{id}
DELETE /alunos/{id}
```

## Estrutura do projeto

```text
studium-api/
├── main.py
├── alunos.py
├── alunos.json
├── requirements.txt
├── .gitignore
└── README.md
```

* `main.py`: contém a aplicação FastAPI e as rotas da API.
* `alunos.py`: contém as operações de cadastro, consulta, atualização e exclusão dos alunos.
* `alunos.json`: armazena os dados dos alunos.

## Tecnologias

* Python
* FastAPI
* JSON

## Instalação

Clone o repositório e acesse a pasta do projeto:

```bash
git clone URL_DO_REPOSITORIO
cd studium-api
```

Crie o ambiente virtual:

```bash
py -m venv .venv
```

No Windows PowerShell, ative o ambiente:

```powershell
.\.venv\Scripts\Activate.ps1
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

## Ambiente virtual

O projeto utiliza um ambiente virtual Python para manter suas dependências isoladas.

A pasta `.venv` deve permanecer apenas no ambiente local e não deve ser enviada para o repositório.

No arquivo `.gitignore`:

```text
.venv/
```

## Objetivo

Praticar a criação de uma API REST simples com Python e FastAPI, utilizando operações CRUD e armazenamento de dados em arquivo JSON.