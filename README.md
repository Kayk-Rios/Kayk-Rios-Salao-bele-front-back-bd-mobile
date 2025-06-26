
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
```


![image1](https://github.com/user-attachments/assets/16cd17ae-ccc4-4278-9af4-46ce89c01e40)

![image2](https://github.com/user-attachments/assets/0fbb5303-2975-4451-bc73-f32d99931c09)

![image3](https://github.com/user-attachments/assets/7bff38d3-530a-4d57-b73f-5b6d850a87a0)

![image11](https://github.com/user-attachments/assets/093ae1a2-9c8f-4470-99b5-be522ddab5a6)
![image10](https://github.com/user-attachments/assets/986237e5-9308-43c3-81dc-08e3bbb80282)
![image9](https://github.com/user-attachments/assets/418fb220-20a8-4fcb-8542-3ceaef077b58)
![image8](https://github.com/user-attachments/assets/c4544d54-69e1-45bb-8fd8-90ac47bc8936)
![image7](https://github.com/user-attachments/assets/9504f065-f075-4ff8-95e2-e53a76da57d5)
![image6](https://github.com/user-attachments/assets/3fa4f9d7-4b4a-44c2-ad85-5968c9aacda2)
![image4](https://github.com/user-attachments/assets/89d66666-bdb8-4bb2-8758-b9d48f2194d6)


