# 🖥️ Projeto Web Services com Spring Boot e JPA / Hibernate

Este projeto foi desenvolvido com o objetivo de praticar e consolidar conhecimentos em **Java**, utilizando o framework **Spring Boot** e a **JPA / Hibernate** para persistência de dados.

O sistema simula um pequeno e-commerce, com funcionalidades básicas de cadastro de usuários, produtos, categorias, pedidos e pagamentos, além de seus relacionamentos.

---

## 🚀 Tecnologias utilizadas

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- H2 Database (banco de dados em memória para testes)
- Maven

---

## 🧩 Objetivos do projeto

- Criar um projeto Spring Boot
- Implementar o modelo de domínio
- Estruturar as camadas lógicas: **resource**, **service** e **repository**
- Configurar banco de dados de teste (H2)
- Povoar o banco de dados com dados iniciais
- Implementar operações **CRUD (Create, Retrieve, Update, Delete)**
- Implementar tratamento de exceções

---

## 🗃️ Modelo de Domínio
<img width="964" height="487" alt="image" src="https://github.com/user-attachments/assets/6e50bb56-cd0b-41f2-967f-85604e74d715" />


---

## 📊 Instância do Domínio (dados de exemplo)
<img width="977" height="573" alt="image" src="https://github.com/user-attachments/assets/c159be35-b1eb-4385-9804-bfd38b681250" />


---

## ⚙️ Como executar o projeto

```bash
# clonar o repositório
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git

# entrar na pasta do projeto
cd NOME-DO-REPOSITORIO

# executar o projeto
./mvnw spring-boot:run

O projeto irá iniciar em:
http://localhost:8080

📌 Endpoints principais

GET /users - Lista todos os usuários

GET /products - Lista todos os produtos

GET /orders - Lista todos os pedidos

GET /categories - Lista todas as categorias
```

## 📚 Aprendizados

Esse projeto foi desenvolvido como parte dos meus estudos fora da faculdade, e me ajudou a entender de forma prática conceitos fundamentais do desenvolvimento back-end com o ecossistema Spring.
