#  Projeto Impacta - Cadastro de Clientes

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Node.js](https://img.shields.io/badge/Back--end-Node.js-brightgreen)
![React](https://img.shields.io/badge/Front--end-React-blue)
![MySQL](https://img.shields.io/badge/Banco-MySQL-orange)

**Descrição:**  
Projeto de exemplo para **Cadastro de Clientes**, utilizando **React** no front-end, **Node.js/Express** no back-end e **MySQL** como banco de dados.  
O projeto demonstra funcionalidades de cadastro, listagem, atualização e exclusão de clientes.

---

## 🔧 Pré-requisitos

Antes de rodar o projeto, certifique-se de ter os seguintes itens instalados:

- **Node.js**
- **MySQL Server**: 
- **MySQL Workbench**
---

## 🔹 Rodando o Backend

1. Abra o terminal na pasta do backend:
cd C:\Users\ADM\Desktop\Projeto Impacta\backend

2. Instale as dependências (apenas na primeira vez): npm install

3. Inicie o servidor: node server.js

Deve aparecer:
Servidor rodando na porta 5000 🚀
Conectado ao MySQL com sucesso!

---

## 🔹 Rodando o Frontend

1. Abra outro terminal na pasta do frontend:
cd C:\Users\ADM\Desktop\Projeto Impacta\frontend

2. Instale as dependências (apenas na primeira vez): npm install

3. Inicie o frontend: npm start

O navegador abrirá automaticamente em:  
[http://localhost:3000/](http://localhost:3000/)

---

## 🔹 Testando o Cadastro

1. Preencha o formulário e clique em **Cadastrar-se**.  
2. Verifique no MySQL Workbench:
USE cadastro;
SELECT * FROM clientes;

O cliente cadastrado deverá aparecer na tabela.
