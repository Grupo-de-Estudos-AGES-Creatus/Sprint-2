# Sprint 2 - API de Filmes 🎬🚀

## Visão Geral

Bem-vindo ao repositório da Sprint 2 do nosso grupo de estudo! Nesta sprint, vamos aprender os conceitos básicos de Backend utilizando Express.js, Prisma e SQLite. O objetivo é desenvolver uma API para filmes, onde o usuário poderá criar, editar e deletar filmes, além de realizar reviews para um filme específico.

A partir da API de Filmes, cada filme poderá ter suas informações básicas, como título, descrição, diretor, ano de lançamento e gênero. Para cada filme, os usuários poderão adicionar suas análises e avaliações por meio de reviews, que serão vinculadas ao filme específico através do seu ID. Esse cruzamento entre filmes e suas reviews permitirá que os usuários explorem as avaliações de cada filme💡✨

---

## 📚 Materiais e Tutoriais

Aqui você encontrará links e referências para facilitar o aprendizado:

- **Express.js**: [Tutorial do Express.js](https://expressjs.com/pt-br/) 🎥
- **Prisma**: [Tutorial do Prisma](https://www.prisma.io/docs/getting-started/quickstart-sqlite) 🎥
- **SQLite**: [Documentação do SQLite](https://www.sqlite.org/docs.html) 📖

---

## 🚀 Descrição da Sprint

### Objetivo

Desenvolver uma API que permita ao usuário:

- Criar filmes 📜
- Editar filmes
- Ler filmes
- Deletar filmes
- Criar novas reviews 🎯
- Editar reviews existentes ✏️
- Ler todas as reviews de um filme específico
- Deletar reviews indesejadas 🗑️

### Funcionalidades Principais

- **CRUD** CRUD para filmes
- **CRUD** para reviews de filmes
- Integração com **SQLite** utilizando **Prisma**
- Validação de dados com **middlewares** (opcional)

---

## 📺 Vídeos

- [RESTful APIs in 100 Seconds // Build an API from Scratch with Node.js Express](https://www.youtube.com/watch?v=-MTSQjw5DrM&t=260s&ab_channel=Fireship)

---

# Verbos HTTP (Métodos HTTP)

Os verbos HTTP definem a ação que um cliente deseja executar em um recurso específico (identificado por uma URL). São essenciais para comunicação web e operações **CRUD** (_Create, Read, Update, Delete_) em APIs RESTful.

---

## Principais Verbos HTTP

### **GET**

- **Função**: Solicitar dados de um recurso (apenas leitura).
- **Características**:
  - Não altera o estado do servidor.
  - Dados enviados via URL (parâmetros de query).
  - Cacheável e seguro (sem efeitos colaterais).

### **POST**

- **Função**: Criar um novo recurso ou enviar dados para processamento.
- **Características**:
  - Modifica o estado do servidor.
  - Dados enviados no corpo da requisição (_body_).

### **PUT**

- **Função**: Atualizar **totalmente** um recurso existente.
- **Características**:
  - Substitui todos os dados do recurso.
  - Requer envio de todos os campos, mesmo não alterados.

### **PATCH**

- **Função**: Atualizar **parcialmente** um recurso.
- **Características**:
  - Modifica apenas os campos especificados.

### **DELETE**

- **Função**: Remover um recurso permanentemente.

---

## Respostas HTTP

O servidor responde com os seguintes componentes:

### **Status Code**

Código de 3 dígitos que indica o resultado da requisição:

| Categoria                  | Exemplos                           | Descrição                       |
| -------------------------- | ---------------------------------- | ------------------------------- |
| **2xx (Sucesso)**          | `200 OK`, `201 Created`            | Requisição bem-sucedida.        |
| **3xx (Redirecionamento)** | `301 Moved Permanently`            | Indica redirecionamento de URL. |
| **4xx (Erro do cliente)**  | `404 Not Found`, `400 Bad Request` | Erros causados pelo cliente.    |
| **5xx (Erro do servidor)** | `500 Internal Server Error`        | Falhas no lado do servidor.     |

---

---

## 🛠️ Tecnologias Utilizadas

- **Node.js** com **Express.js**
- **Prisma ORM**
- **SQLite** (ou **Postgres**, se preferir)
- **JavaScript** (ou **TypeScript**, se preferir)

## 🎯 Próximos Passos

- Adicionar testes unitários 🧪
- Implementar autenticação e autorização 🔒
- Melhorar a documentação da API 📖

---

Divirta-se codando e bons estudos! 🚀✨

---
