
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

![image11](https://github.com/user-attachments/assets/c4425924-d71e-4ec6-a7e5-0e1217208914)

![image10](https://github.com/user-attachments/assets/dbd30acc-25e6-4904-b38c-548ae75eba2e)

![image9](https://github.com/user-attachments/assets/7cd56557-1c8e-4688-9a80-47e1ab227993)

![image8](https://github.com/user-attachments/assets/48305fc1-49b1-4cac-931b-c6f81291256e)

![image7](https://github.com/user-attachments/assets/3b876393-ab46-49ac-a96e-f7a6ef80f70d)

![image6](https://github.com/user-attachments/assets/c4d4eac0-7215-4f49-b215-343ce84d526d)

![image4](https://github.com/user-attachments/assets/b592d786-acf6-4fc2-bfab-a58137edc605)

![image3](https://github.com/user-attachments/assets/7a800025-4cdb-4c97-a0ad-6e07bbdef559)

![image2](https://github.com/user-attachments/assets/d96de956-c52e-4085-8bd0-70f1f8d99bc3)

![image1](https://github.com/user-attachments/assets/c2684dff-a3b9-4a80-871e-bcf82e7c75cc)




