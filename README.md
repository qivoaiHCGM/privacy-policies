# Política de Privacidade - Qivo AI

Este repositório contém a Política de Privacidade da Qivo AI para integração com as APIs da Meta (Facebook, Instagram, WhatsApp).

## 🚀 Como hospedar no GitHub Pages (GRATUITO)

Siga estes passos para publicar sua política de privacidade:

### Passo 1: Criar repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique no botão **"+"** no canto superior direito e selecione **"New repository"**
3. Dê um nome ao repositório (ex: `privacy-policy` ou `politica-privacidade`)
4. Marque como **Public** (necessário para GitHub Pages gratuito)
5. Clique em **"Create repository"**

### Passo 2: Fazer upload dos arquivos

Você tem duas opções:

#### Opção A - Via linha de comando (se já tem Git instalado):

```bash
# Na pasta do projeto, execute:
git init
git add .
git commit -m "Adiciona política de privacidade"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
git push -u origin main
```

**Substitua** `SEU-USUARIO` e `SEU-REPOSITORIO` pelos seus dados reais.

#### Opção B - Via interface do GitHub (mais fácil):

1. No repositório recém-criado, clique em **"uploading an existing file"**
2. Arraste o arquivo `index.html` para a área de upload
3. Clique em **"Commit changes"**

### Passo 3: Ativar GitHub Pages

1. No seu repositório, clique em **"Settings"** (Configurações)
2. No menu lateral esquerdo, clique em **"Pages"**
3. Em **"Source"**, selecione:
   - Branch: **main**
   - Folder: **/ (root)**
4. Clique em **"Save"**
5. Aguarde 1-2 minutos para o site ser publicado

### Passo 4: Obter a URL

Após alguns minutos, você verá uma mensagem:

```
Your site is live at https://SEU-USUARIO.github.io/SEU-REPOSITORIO/
```

**Esta é a URL que você deve fornecer para a Meta!**

## 📝 URL para a Meta

Depois de publicado, sua política de privacidade estará disponível em:

```
https://SEU-USUARIO.github.io/SEU-REPOSITORIO/
```

Use esta URL nos seguintes campos do Meta for Developers:
- **Privacy Policy URL** (URL da Política de Privacidade)
- **Terms of Service URL** (se solicitado)

## 🔄 Como atualizar a política

Se precisar fazer alterações:

1. Edite o arquivo `index.html` localmente
2. Faça o upload novamente (via Git ou interface do GitHub)
3. O site será atualizado automaticamente em 1-2 minutos

## ✅ Verificação

Para verificar se está funcionando:

1. Acesse a URL do GitHub Pages no navegador
2. Verifique se a política está sendo exibida corretamente
3. Teste em dispositivos móveis para garantir a responsividade

## 📧 Contato

**E-mail:** qivoai@gmail.com
**Website:** https://qivoai.com.br

---

## Alternativas ao GitHub Pages

Se preferir outras opções de hospedagem gratuita:

- **Netlify Drop:** [drop.netlify.com](https://app.netlify.com/drop) - Arraste e solte o arquivo HTML
- **Vercel:** [vercel.com](https://vercel.com) - Conecte seu repositório GitHub
- **GitLab Pages:** Similar ao GitHub Pages
- **Cloudflare Pages:** [pages.cloudflare.com](https://pages.cloudflare.com)

Todas essas opções são gratuitas e adequadas para hospedar páginas estáticas.

