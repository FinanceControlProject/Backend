# API DE GERENCIAMENTO DE FINANÇAS PESSOAIS

## Funcionalidades e como utilizar a API de Gerenciamento de Finanças Pessoais. A API foi desenvolvida com **Node.js**, **Express**, **Prisma** e **MongoDB**, seguindo boas práticas de organização e segurança.

---

## 🚀 Visão Geral

A API permite que usuários gerenciem suas finanças pessoais, incluindo:

- **Cadastro e autenticação de usuários**.
- **Registro de transações** (receitas e despesas).
- **Consulta de extrato financeiro**.
- **Validação de dados** para garantir consistência e segurança.

---

## 📂 Estrutura do Projeto

A estrutura do projeto foi organizada para facilitar a manutenção e escalabilidade:
- **/prisma**
  - `schema.prisma`
- **/src**
  - **/config**
    - `prismaClient.js`
  - **/middlewares**
    - `authMiddleware.js`
    - `validateMiddleware.js`
  - **/models**
    - `userModel.js`
    - `transactionModel.js`
  - **/controllers**
    - `userController.js`
    - `transactionController.js`
  - **/routes**
    - **/public**
      - `userRoutes.js`
    - **/private**
      - `transactionRoutes.js`
  - `app.js`
  - `server.js`
- **Arquivos na Raiz**
  - `.env`
  - `package.json`
  - `README.md`


