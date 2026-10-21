# CapiReps — Política de Privacidade

Página pública da política de privacidade do app **CapiReps** (Capivara
Studios), pronta para o **GitHub Pages**.

- `index.html` — página completa (pt-BR/en, responsiva, autocontida)
- `privacy-policy.md` — a mesma política em Markdown
- `.nojekyll` — evita o processamento do Jekyll no Pages

## Publicar no GitHub Pages

1. Crie um repositório **público** chamado `capireps-privacy` no GitHub.
2. Envie estes arquivos:

   ```bash
   git add .
   git commit -m "docs: política de privacidade do CapiReps"
   git branch -M main
   git remote add origin https://github.com/<seu-usuario>/capireps-privacy.git
   git push -u origin main
   ```

3. No GitHub: **Settings → Pages → Build and deployment**
   - **Source:** Deploy from a branch
   - **Branch:** `main` · **Folder:** `/ (root)` → **Save**

4. Em cerca de 1 minuto a URL fica:
   `https://<seu-usuario>.github.io/capireps-privacy/`

5. Use essa URL no **Google Play Console** em
   **Conteúdo do app → Política de privacidade**.

> No plano gratuito, o repositório precisa ser **público** para usar o GitHub
> Pages.

## Atualizar

Edite `index.html` (ou `privacy-policy.md`), faça commit e push. O GitHub Pages
republica automaticamente em ~1 minuto.

## Pré-visualizar localmente

```bash
npx serve .
```

Ou abra `index.html` diretamente no navegador.

## Contato

contato.capistudios@gmail.com
