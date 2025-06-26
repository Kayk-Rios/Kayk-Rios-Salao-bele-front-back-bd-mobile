
# 💇‍♀️ Salão Belê - Monorepo

Repositório monolítico contendo as aplicações **Web (Next.js)**, **Mobile (React Native)** e **Backend (NestJS)**, organizadas para o gerenciamento de um salão de beleza.

---

## 📦 Estrutura do Projeto

salao-bele/
│

├── frontend/ # Aplicação Web com Next.js

├── backend/ # API com NestJS + Prisma + PostgreSQL

└── mobile/ # Aplicação Mobile com React Native (Expo)



## 🚀 Tecnologias Principais

- **Next.js** + **TypeScript** (Web)
- **React Native** + **Expo** (Mobile)
- **NestJS** (Backend)
- **PostgreSQL** (Banco de dados)
- **Prisma** (ORM)

---

## 🌐 Aplicação Web

🔗 Acesse em produção:  
**https://salao-bele.netlify.app/**

### ▶️ Como rodar localmente

```bash
cd frontend
yarn dev
📱 Aplicação Mobile
Aplicação construída com React Native + Expo Router.

▶️ Como rodar

cd mobile
yarn install
yarn dev
Você pode escolher entre:

yarn android

yarn ios

yarn web

🛠️ Backend (NestJS + Prisma)
O backend fornece as APIs REST e integrações com o banco de dados PostgreSQL.

▶️ Como rodar

cd backend
yarn install
yarn run dev
🗃️ Configuração do Banco de Dados
Para conectar o backend a um banco de dados PostgreSQL:

Copie o arquivo .env.sample localizado na pasta backend.

Renomeie para .env.

Atualize a variável DATABASE_URL com sua conexão PostgreSQL, por exemplo:

env
DATABASE_URL="postgresql://user:password@localhost:5432/salao_db"
Execute as migrations:

bash
npx prisma migrate dev
✅ Scripts Importantes
Backend (/backend)
yarn dev: Inicia o servidor em modo de desenvolvimento

yarn build: Compila o projeto

yarn test: Executa testes unitários e2e

npx prisma studio: Abre o painel visual do Prisma

Frontend (/frontend)
yarn dev: Inicia o servidor Next.js

yarn build: Gera a aplicação para produção

Mobile (/mobile)
yarn dev: Inicia o Expo

yarn android / yarn ios: Executa no simulador

yarn web: Executa a versão web do app mobile




![5](https://github.com/user-attachments/assets/dc5fcd9c-808c-46a8-a1c5-cdf505d8e042)

![6](https://github.com/user-attachments/assets/3813dfde-76d7-4c25-b3c2-26489dcf52c0)

![7](https://github.com/user-attachments/assets/cd88c2e7-e889-4b03-b7d5-279680ac6f07)

![8](https://github.com/user-attachments/assets/14540175-da51-469d-8b58-0c96e277aeac)

Mobile

![1](https://github.com/user-attachments/assets/cc2a4f3b-9e45-4765-b1d9-135198d32ef5)

![2](https://github.com/user-attachments/assets/2cea9a5a-3167-4a50-9df4-7cf9841c5afd)

![3](https://github.com/user-attachments/assets/5aa5be83-dc66-44df-a524-ee5564eb3bcb)

![4](https://github.com/user-attachments/assets/404543a4-1488-4b60-a6cc-1dfb6b82c906)
