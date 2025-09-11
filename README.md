#  Projeto Impacta - Cadastro de Clientes

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Node.js](https://img.shields.io/badge/Back--end-Node.js-brightgreen)
![React](https://img.shields.io/badge/Front--end-React-blue)
![MySQL](https://img.shields.io/badge/Banco-MySQL-orange)

**Descrição:**  
Projeto de exemplo para **Cadastro de Clientes**, utilizando **React** no front-end, **Node.js/Express** no back-end e **MySQL** como banco de dados.  
O projeto demonstra funcionalidades de cadastro, listagem, atualização e exclusão de clientes.


# 🚀 Como rodar:

1. Abra o terminal na pasta do backend:
```bash
cd C:\Users\ADM\Desktop\Projeto Impacta\backend
Instale as dependências (apenas na primeira vez):

bash
Copiar código
npm install
Inicie o servidor:

bash
Copiar código
node server.js
Deve aparecer:

yaml
Copiar código
Servidor rodando na porta 5000 🚀
Conectado ao MySQL com sucesso!

🔹 Rodando o Frontend
Abra outro terminal na pasta do frontend:

bash
Copiar código
cd C:\Users\ADM\Desktop\Projeto Impacta\frontend
Instale as dependências (apenas na primeira vez):

bash
Copiar código
npm install
Inicie o frontend:

bash
Copiar código
npm start
O navegador abrirá automaticamente em:
http://localhost:3000/

🔹 Testando o Cadastro
Preencha o formulário e clique em Cadastrar-se.

Verifique no MySQL Workbench:

sql
Copiar código
USE cadastro;
SELECT * FROM clientes;
