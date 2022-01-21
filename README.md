# API com Node, TS e Typeorm

## Como inicializar a aplicação

---
    npm run dev
---

## Como instanciar o banco de dados 

---
    npm typeorm migration:run
---

### Comandos uteis para criar o projeto do zero

- npm init --y
- npm i typescript ts-node-dev -D
- npx tsc --init
- npm i express sqlite3 typeorm uuid reflect-metada
- npm i @types/express @types/uuid -D
- npm i jest @types/jest ts-jest -D
- npm jest --init

### Rotas

- GET - http://localhost:5000/
- POST - http://localhost:5000/usuários
---
    {
        "nome": "",
        "email": ""
    }
---

- GET - http://localhost:5000/usuários
- PATCH - http://localhost:5000/usuário
---
    {
        "id": "",
        "nome": "",
        "email": ""
    }
---
- DEL - http://localhost:5000/usuário/
Inserir ao final da URL, o id do usuário a ser deletado.
