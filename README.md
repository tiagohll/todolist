# 🚀 To-Do List API (Rocketseat Java Course)

Este é um projeto de gerenciamento de tarefas (To-Do List) desenvolvido durante o curso de Java da **Rocketseat**. A aplicação foca no desenvolvimento do backend, explorando conceitos de autenticação, persistência de dados e boas práticas com o ecossistema Spring.

> **Status:** Concluído ✔️

---

## 🛠️ Tecnologias e Ferramentas

O projeto foi construído utilizando as seguintes tecnologias:

* **Java 17**
* **Spring Boot 3**
* **Spring Data JPA** (Persistência de dados)
* **H2 Database** (Banco de dados em memória para testes)
* **BCrypt** (Para criptografia de senhas)
* **Maven** (Gerenciador de dependências)

---

## ✨ Funcionalidades

* **Cadastro de Usuário:** Criação de conta com senha criptografada.
* **Autenticação:** Sistema de login seguro.
* **Gestão de Tarefas:**
    * Criar uma nova tarefa vinculada ao usuário logado.
    * Listar todas as tarefas do usuário.
    * Atualizar informações de uma tarefa existente.
    * Definição de prioridade (Alta, Média, Baixa) e prazos.

---

## 🚀 Como Executar o Projeto

Para rodar a aplicação localmente, siga os passos abaixo:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/tiagohll/todolist.git](https://github.com/tiagohll/todolist.git)
   ```
2. **Entre na pasta do projeto:**
   ```bash
   cd todolist
   ```
3. **Instale as dependências e compile:**
   ```bash
   ./mvnw clean install
   ```
4. **Execute a aplicação:**
   ```bash
   ./mvnw spring-boot:run
   ```

A API estará disponível em http://localhost:8080.

## 📡 Endpoints Principais

| Método | Endpoint | Descrição |
| :--- | :--- | :--- |
| `POST` | `/users/` | Cadastra um novo usuário |
| `POST` | `/tasks/` | Cria uma nova tarefa |
| `GET`  | `/tasks/` | Lista tarefas do usuário autenticado |
| `PUT`  | `/tasks/{id}` | Atualiza uma tarefa existente |

## 🎓 Aprendizados
Neste projeto, pude aprofundar conhecimentos em:

* Estruturação de camadas (Controller, Model, Repository).

* Manipulação de exceções personalizadas no Spring.

* Segurança e criptografia básica.

* Relacionamento entre entidades (Usuário x Tarefa).
