# 🔐 Spring Boot Authentication System

Sistema de autenticação e cadastro de usuários desenvolvido com **Java + Spring Boot + Spring Data JPA + MySQL**.

Projeto criado com foco em estudo e prática de arquitetura MVC, persistência de dados e autenticação básica.

---

## 🚀 Tecnologias Utilizadas

- Java 17+
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate
- MySQL
- Jakarta Validation
- Maven

---

## 📌 Funcionalidades

- ✅ Cadastro de usuários
- ✅ Login com validação de credenciais
- ✅ Redirecionamento para dashboard após autenticação
- ✅ Validação de campos obrigatórios
- ✅ Persistência de dados com JPA
- ✅ Query personalizada para autenticação

---

## 🏗 Arquitetura

O projeto segue o padrão **MVC (Model-View-Controller)**:

- **Model** → Entidade `Usuario`
- **Repository** → Interface `UsuarioRepository`
- **Controller** → `LoginController`
- **View** → Páginas HTML (login, cadastro e dashboard)

---

## 🗄 Banco de Dados

Banco utilizado: **MySQL**

Configuração manual de DataSource e Hibernate:

- Driver: `com.mysql.cj.jdbc.Driver`
- Dialect: `MariaDBDialect`
- Geração automática de tabelas habilitada

---

## ▶️ Como Executar

1. Clonar o repositório:

```bash
git clone https://github.com/seuusuario/springboot-authentication-system.git
