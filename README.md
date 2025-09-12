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

⚡ Como Rodar

🔹 Backend

cd backend
npm install
# Configure sua senha do MySQL no server.js
node server.js

---

Servidor rodando na porta 5000.

🔹 Frontend

cd frontend
npm install
npm start


Acesse no navegador: http://localhost:3000

---

📝 Cadastro

Preencha o formulário de clientes ou equipamentos.

Clique em Cadastrar.

Verifique no MySQL Workbench:

USE cadastro;
SELECT * FROM clientes;        -- ou
SELECT * FROM equipamentos;


⚠️ Importante: configure a senha do MySQL no arquivo server.js.

---
