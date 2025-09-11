#  Projeto Impacta - Cadastro de Clientes

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Node.js](https://img.shields.io/badge/Back--end-Node.js-brightgreen)
![React](https://img.shields.io/badge/Front--end-React-blue)
![MySQL](https://img.shields.io/badge/Banco-MySQL-orange)

**Descrição:**  
Projeto de exemplo para **Cadastro de Clientes**, utilizando **React** no front-end, **Node.js/Express** no back-end e **MySQL** como banco de dados.  
O projeto demonstra funcionalidades de cadastro, listagem, atualização e exclusão de clientes.


# 🚀 Como rodar:

# 🚀 Projeto Impacta - Cadastro de Clientes

## 🔹 Rodando o Backend

1. Abra o terminal na pasta do backend:
cd C:\Users\ADM\Desktop\Projeto Impacta\backend

csharp
Copiar código

2. Instale as dependências (apenas na primeira vez):
npm install

markdown
Copiar código

3. Inicie o servidor:
node server.js

yaml
Copiar código

Deve aparecer:
Servidor rodando na porta 5000 🚀
Conectado ao MySQL com sucesso!

yaml
Copiar código

---

## 🔹 Rodando o Frontend

1. Abra outro terminal na pasta do frontend:
cd C:\Users\ADM\Desktop\Projeto Impacta\frontend

csharp
Copiar código

2. Instale as dependências (apenas na primeira vez):
npm install

markdown
Copiar código

3. Inicie o frontend:
npm start

yaml
Copiar código

O navegador abrirá automaticamente em:  
[http://localhost:3000/](http://localhost:3000/)

---

## 🔹 Testando o Cadastro

1. Preencha o formulário e clique em **Cadastrar-se**.  
2. Verifique no MySQL Workbench:
USE cadastro;
SELECT * FROM clientes;

mathematica
Copiar código

O cliente cadastrado deverá aparecer na tabela.
