# Store API - Desafio de Projeto DIO

## 📄 Descrição do Projeto

Este projeto consiste na construção de uma API REST para o gerenciamento de produtos de uma loja (e-commerce). A aplicação foi desenvolvida como parte do desafio de projeto da [Digital Innovation One (DIO)](https://www.dio.me/) para aplicar e solidificar conceitos de desenvolvimento backend com Python e FastAPI.

A API permite realizar operações CRUD (Criar, Ler, Atualizar, Deletar) para os produtos da loja, servindo como uma base robusta para um sistema de e-commerce.

## 🎯 Sobre o Desafio
O foco principal foi a aplicação prática dos seguintes conceitos:

  - Construção de endpoints RESTful com FastAPI.
  - Interação com banco de dados utilizando um ORM (SQLAlchemy).
  - Validação de dados com Pydantic para garantir a integridade das requisições.
  - Gerenciamento de migrações de banco de dados com Alembic.
  - Boas práticas de estruturação de um projeto de API.


## 🚀 Tecnologias Utilizadas

  - **Python 3.10+**
  - **FastAPI:** Framework web de alta performance para a construção da API.
  - **SQLAlchemy:** ORM para a comunicação com o banco de dados.
  - **PostgreSQL / SQLite:** Sistema de gerenciamento de banco de dados relacional.
  - **Alembic:** Ferramenta para versionamento e controle de migrações do schema do banco de dados.
  - **Pydantic:** Biblioteca para validação de dados e gerenciamento de configurações.
  - **Uvicorn:** Servidor ASGI (Asynchronous Server Gateway Interface) para executar a aplicação.

## 🕹️ API Endpoints

A API fornece endpoints para gerenciar produtos. Abaixo estão alguns exemplos:

| Método | Endpoint         | Descrição                  |
| :----- | :--------------- | :------------------------- |
| `POST` | `/products`      | Cria um novo produto.      |
| `GET`  | `/products/{id}` | Busca um produto pelo ID.  |
| `GET`  | `/products`      | Lista todos os produtos.   |
| `PUT`  | `/products/{id}` | Atualiza um produto.       |
| `DELETE`| `/products/{id}` | Deleta um produto.         |

### Exemplo: Criando um novo produto

`POST /products`

**Payload de exemplo:**

```json
{
  "name": "Smartphone Modelo X",
  "quantity": 50,
  "description": "Um smartphone com câmera de 108MP e tela AMOLED.",
  "price": 2999.99,
  "status": true
}
```

## 👨‍💻 Autor

[Linkedin](https://www.google.com/search?q=https://www.linkedin.com/in/emmanuelmonteiro/)

[GitHub](https://www.google.com/search?q=https://github.com/EmmanuelGBL)

## 🙏 Agradecimentos

Agradeço à [Digital Innovation One](https://www.dio.me/) pelo desafio, que foi fundamental para a prática e aprofundamento dos meus conhecimentos em desenvolvimento backend.

