# 🛒 Mercadão Vem Que Tem

Sistema completo de cadastro, login e gerenciamento de estoque de produtos, desenvolvido com Node.js, Express, TypeORM, MySQL e front-end com HTML, CSS e JavaScript puro.

---

## 📁 Estrutura do Projeto

├── src
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── database/
│ ├── .env
│ └── server.ts
├── public
│ ├── css/
│ ├── js/
│ ├── img/
│ ├── cadastro.html
│ ├── login.html
│ └── home.html

yaml
Copiar
Editar

---

## 🚀 Funcionalidades

### 🔐 Autenticação de Usuários
- Cadastro de usuários com senha criptografada (`bcrypt`)
- Login com verificação de senha
- Redirecionamento após login/cadastro

### 📦 Gerenciamento de Produtos
- Cadastrar novos produtos
- Buscar produto por ID
- Listar todos os produtos
- Editar e deletar produtos

---

## 💡 Tecnologias Utilizadas

### Backend
- Node.js
- Express
- TypeORM
- MySQL
- bcryptjs
- dotenv

### Frontend
- HTML5
- CSS3
- JavaScript (puro)

---

## ⚙️ Configuração e Execução

### Pré-requisitos
- Node.js instalado
- MySQL rodando
- Editor de código (VSCode recomendado)

### 1. Clone o projeto
```bash
git clone https://github.com/seu-usuario/mercadao.git
cd mercadao

2. Instale as dependências do backend

bash
Copiar
Editar
cd backend
npm install

3. Configure o .env

Crie o arquivo .env no diretório backend/ com o seguinte conteúdo:

ini
Copiar
Editar
DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=root
DB_NAME=trabalho

4. Crie o banco de dados no MySQL

sql
Copiar
Editar
CREATE DATABASE trabalho;

5. Execute as migrations (se houver)

bash
Copiar
Editar
npm run typeorm migration:run

6. Inicie o servidor

bash
Copiar
Editar
npm run dev

7. Acesse o sistema

Abra o arquivo public/login.html no navegador ou use uma extensão como o Live Server do VSCode.

📌 Próximos Passos
 Implementar autenticação com JWT

 Proteger rotas com middleware

 Melhorar UI/UX (ex: modais e loaders)

 Refatorar código JS com módulos