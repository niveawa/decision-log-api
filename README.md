# Decision Log API

API REST para registro de decisões associadas a projetos.

O foco do projeto é demonstrar organização, clareza de escopo e boas práticas em um sistema simples, sem complexidade desnecessária.

---

## Escopo da V1

- Login de usuário
- CRUD de projetos
- CRUD de decisões
- Listagem com paginação
- Validação de dados
- Autenticação via JWT

---

## Fora de escopo (por enquanto)

- Controle avançado de permissões
- Comentários
- Versionamento de decisões
- Upload de arquivos
- OAuth / autenticação externa

Esses itens ficam como melhorias futuras.

---

## Stack

- Java 17
- Spring Boot
  - Spring Web
  - Spring Data JPA
  - Spring Security
- PostgreSQL
- Flyway
- JWT

---

## Domínio

- **User** → possui projetos
- **Project** → agrupa decisões
- **Decision** → registra contexto e decisão tomada

---
