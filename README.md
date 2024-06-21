# Student CRUD App

## Descrição do Projeto

Este projeto é um aplicativo web para gerenciamento de cadastro de estudantes, utilizando Next.js no frontend e NestJS no backend. O projeto é containerizado utilizando Docker e Docker Compose.

## Estrutura do Projeto

- `backend`: Diretório contendo o backend do NestJS.
- `frontend`: Diretório contendo o frontend do Next.js.

## Como Rodar o Projeto

### Requisitos

- Docker
- Docker Compose

### Passos

1. Clone o repositório:

    ```zsh
    git clone https://github.com/juulioclf/sistema_alunos_fpf.git
    cd sistema_alunos_fpf
    ```

2. Inicie os contêineres:

    ```zsh
    docker-compose up --build
    ```

3. Acesse a aplicação:

    - Frontend: [http://localhost:3000](http://localhost:3000)
    - Backend: [http://localhost:3001](http://localhost:3001)

## Tecnologias Utilizadas

- Frontend: Next.js
- Backend: NestJS
- Banco de Dados: PostgreSQL
- Containerização: Docker, Docker Compose
