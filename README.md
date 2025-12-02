```bash
 ## Visão Geral dos Recursos do Aplicativo
🔐 Autenticação com verificação de e-mail usando Clerk

📝 Fluxos de Cadastro e Login com código de 6 dígitos por e-mail

🏠 Tela Inicial que mostra seu saldo atual e transações passadas

➕ Tela de Criação para adicionar transações de receita (income) ou despesa (expense)

🔄 Funcionalidade de "Pull to refresh" (puxar para atualizar) construída do zero

🗑️ Excluir transações para atualizar o saldo

🚪 Sair (Logout) para navegar de volta para a tela de login
```

## 📁 .env Setup

### ⚙️ Backend (`/backend`)

```bash
PORT=5001
NODE_ENV=development

CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
CLERK_SECRET_KEY=<your_clerk_secret_key>

DATABASE_URL=<your_neon_postgres_connection_url>

REDIS_URL=<your_redis_connection_url>
```

### ⚙️ Backend (`/backend`)

```bash
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_key>
```

## Executar o Backend

```bash
cd backend
npm install
npm run dev

```

## Executar o Mobile

```bash
cd mobile
npm install
npx expo start
```
