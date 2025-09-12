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

🚀 Guia Rápido: Projeto de Cadastro de Clientes e Equipamentos

🔹 Backend

Abra o terminal na pasta do backend:

cd C:\Users\ADM\Desktop\Projeto Impacta\backend


Instale dependências (somente na primeira vez):

npm install


Configure a senha do MySQL no server.js:

const db = mysql.createConnection({
  host: "127.0.0.1",
  port: 3306,
  user: "root",
  password: "SUA_SENHA_AQUI", // <-- substitua pela senha do seu MySQL
  database: "cadastro",
});


Inicie o servidor:

node server.js


Deve aparecer:

Servidor rodando na porta 5000 🚀
Conectado ao MySQL com sucesso!

🔹 Frontend

Abra outro terminal na pasta do frontend:

cd C:\Users\ADM\Desktop\Projeto Impacta\frontend


Instale dependências (somente na primeira vez):

npm install


Inicie o frontend:

npm start


O navegador abrirá automaticamente em:

http://localhost:3000/

🔹 Cadastro de Clientes

Acesse a página de cadastro de clientes.

Preencha o formulário com os dados obrigatórios.

Clique em Cadastrar-se.

Verifique no MySQL Workbench:

USE cadastro;
SELECT * FROM clientes;


O cliente cadastrado deverá aparecer na tabela.

🔹 Cadastro de Equipamentos

Acesse a página de cadastro de equipamentos.

Preencha o formulário com os campos:

Nome do equipamento

Marca

Modelo

Número de série

Patrimônio

Status (Em uso, Em manutenção, Reservado, Sucata)

Localização

Responsável

Data de aquisição

Fim da garantia

Observações

Clique em Cadastrar.

Verifique no MySQL Workbench:

USE cadastro;
SELECT * FROM equipamentos;


O equipamento cadastrado deverá aparecer na tabela.
