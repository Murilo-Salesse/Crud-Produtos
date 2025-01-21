# Produtos API

Este é um projeto simples de CRUD para gerenciamento de produtos, desenvolvido em **Java** com **Spring Boot**. Ele fornece endpoints RESTful para criar, consultar, atualizar e excluir produtos.

---

## 🛠️ Tecnologias utilizadas

- **Java 17** (ou versão compatível)
- **Spring Boot**
- **Spring Data JPA**
- **H2 Database** (ou qualquer outro banco de dados configurado)
- **Maven**

---

## 🚀 Funcionalidades

- **Criar produto**: Adicionar novos produtos com `nome`, `descrição` e `preço`.
- **Consultar produto por ID**: Recuperar os detalhes de um produto específico.
- **Atualizar produto**: Alterar informações de um produto já cadastrado.
- **Deletar produto**: Remover um produto do sistema.
- **Buscar produto por nome**: Listar produtos baseados no nome.

---

## 📦 Modelo de Dados

A classe `Produto` define o modelo da aplicação com os seguintes campos:

- `id` (String): Identificador único do produto.
- `nome` (String): Nome do produto.
- `descricao` (String): Descrição do produto.
- `preco` (Double): Preço do produto.

Exemplo:
```json
{
  "id": "uuid",
  "nome": "Notebook",
  "descricao": "Notebook Dell Inspiron",
  "preco": 3999.99
}
```

Made with ❤️ by Murilo Salesse 👋🏽
