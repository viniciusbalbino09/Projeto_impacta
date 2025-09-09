# 🚀 Projeto Impacta - Cadastro de Clientes

Projeto de cadastro de clientes usando **React** (front-end), **Node.js/Express** (back-end) e **MySQL**.

---

## ⚙️ Como Rodar

### Back-end
```bash
cd backend
npm install
node server.js
Servidor rodando em: http://localhost:5000

Front-end
bash
Copiar código
cd frontend
npm install
npm start
Front-end em: http://localhost:3000

📋 Testar Cadastro
Preencha o formulário no front-end e verifique no MySQL Workbench:

sql
Copiar código
USE cadastro;
SELECT * FROM clientes;
📁 Estrutura
Front-end: Tela de cadastro em React, comunicação via fetch.

Back-end: API REST com Node.js/Express, conecta ao MySQL (mysql2).

Endpoints: GET /clientes, POST /clientes.

Banco de Dados: Tabela clientes com campos:
id, nome_completo, sexo, data_nascimento, email, telefone, cidade, estado, endereco, data_cadastro.

📝 Licença
MIT License © Vinicius Balbino
