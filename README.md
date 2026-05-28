# C: Do Zero ao Mestre

Guia interativo de aprendizado de C com compilador GCC real e IA.

## Deploy no Vercel

### 1. Pegar a Gemini API Key (grátis)
- Acesse [aistudio.google.com](https://aistudio.google.com)
- Clique em **Get API key** → **Create API key**
- Copie a key

### 2. Subir no GitHub
- Crie um repositório novo em [github.com](https://github.com)
- Faça upload de todos os arquivos desta pasta

### 3. Conectar ao Vercel
- Acesse [vercel.com](https://vercel.com) e faça login com sua conta GitHub
- Clique em **Add New Project**
- Selecione seu repositório
- Clique em **Deploy**

### 4. Configurar a API Key
- No painel do Vercel, vá em **Settings → Environment Variables**
- Adicione:
  - **Name:** `GEMINI_API_KEY`
  - **Value:** sua key do Google AI Studio
- Clique em **Save** e depois **Redeploy**

Pronto! O site estará em `https://seu-projeto.vercel.app`

## Estrutura
```
├── index.html      — O guia completo de C
├── api/
│   └── gemini.js   — Função serverless (proxy da IA)
└── vercel.json     — Configuração de rotas
```
