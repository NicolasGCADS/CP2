# 📚 Livraria API 

API RESTful para gerenciamento de livros

---

## 🎯 Objetivo

- Expor endpoints REST para gerenciar livros (CRUD)

### Como usar 

1. Clone o projeto
2. Configure o banco Oracle no appsettings.json
3. | Método | Rota               | Descrição                |
| ------ | ------------------ | ------------------------ |
| GET    | `/api/livros`      | Lista todos os livros    |
| GET    | `/api/livros/{id}` | Retorna livro por ID     |
| POST   | `/api/livros`      | Cria novo livro          |
| PUT    | `/api/livros/{id}` | Atualiza livro existente |
| DELETE | `/api/livros/{id}` | Remove um livro          |
4. Exemplo de Json {
  "id": 1,
  "titulo": "O Senhor dos Anéis",
  "autor": "J.R.R. Tolkien",
  "preco": 89.90,
  "anoPublicacao": 1954
}



