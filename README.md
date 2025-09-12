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

⚡ Como Rodar o Projeto
🔹 Backend

Abra o terminal na pasta do backend:

cd backend
npm install


Configure sua senha do MySQL no arquivo server.js.

Inicie o servidor:

node server.js


✅ Servidor rodando na porta 5000.

---


🔹 Frontend

Abra o terminal na pasta do frontend:

cd frontend
npm install
npm start


Acesse no navegador: http://localhost:3000

---


📝 Cadastro

Preencha o formulário de clientes ou equipamentos.

Clique em Cadastrar.

Verifique os dados no MySQL Workbench:

USE cadastro;
SELECT * FROM clientes;
SELECT * FROM equipamentos;


⚠️ Importante: não esqueça de configurar a senha do MySQL no arquivo server.js.

---

