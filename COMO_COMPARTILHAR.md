# 📊 Como Compartilhar o Dashboard

## Opção 1: GitHub Pages (GRÁTIS) ⭐ RECOMENDADO

1. **Crie um repositório no GitHub**
   - Vá para github.com/new
   - Nome: `dashboard-financeiro`
   - Marque "Public"
   - Clique "Create repository"

2. **Faça upload do arquivo**
   - Clique em "Add file" → "Upload files"
   - Faça upload de `dashboard.html`
   - Commit com mensagem: "Initial dashboard"

3. **Ative GitHub Pages**
   - Vá para Settings → Pages
   - Branch: `main`
   - Folder: `/ (root)`
   - Clique "Save"

4. **Obtenha seu link**
   - GitHub vai gerar: `https://seu-usuario.github.io/dashboard-financeiro/dashboard.html`
   - Compartilhe este link!

---

## Opção 2: Vercel (GRÁTIS)

1. Vá para https://vercel.com/import
2. Importe seu repositório GitHub (da Opção 1)
3. Clique "Deploy"
4. Link automático: `https://seu-projeto.vercel.app/dashboard.html`

---

## Opção 3: Netlify (GRÁTIS)

1. Vá para https://app.netlify.com/drop
2. Arraste `dashboard.html` para a zona de drop
3. Obtém um link automático como: `https://seu-site-random.netlify.app/`

---

## Opção 4: Servidor Próprio

Se você tem um servidor (VPS, hospedagem):
```bash
# Coloque o arquivo no seu servidor
cp dashboard.html /var/www/html/

# Acesse via: https://seu-dominio.com/dashboard.html
```

---

## 🔄 Atualizando o Dashboard

Sempre que atualizar os dados no dashboard React original:

1. Gere o novo `dashboard.html`
2. Faça upload/commit no GitHub (ou qualquer serviço)
3. A página atualiza automaticamente em ~1-5 minutos

---

## ⚠️ Nota Importante

O arquivo HTML carrega **dados do localStorage** do navegador. Para sincronizar dados:

1. Abra o dashboard React original no Claude
2. Faça todas as alterações lá
3. Clique em "Salvar" ou deixe auto-salvar
4. Regenere o `dashboard.html`
5. Faça upload para seu servidor

---

**Recomendação:** Use GitHub Pages (Opção 1) - é grátis, confiável e fácil!
