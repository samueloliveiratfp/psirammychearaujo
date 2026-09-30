# Link da bio | Rammyche Araújo

Site estático (HTML + CSS puro, sem build). Estrutura:

```
index.html          página completa
assets/rammyche.jpg foto do hero
vercel.json         configuração opcional de cache
```

## Publicar no GitHub + Vercel

1. Crie um repositório vazio no GitHub (ex.: `rammyche-linkbio`).
2. Na pasta do projeto:
   ```
   git init
   git add .
   git commit -m "site inicial"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/rammyche-linkbio.git
   git push -u origin main
   ```
3. Em vercel.com: **Add New > Project**, importe o repositório.
   - Framework Preset: **Other**
   - Build Command: deixe vazio
   - Output Directory: deixe vazio (raiz)
   - Clique em **Deploy**.
4. Cole a URL gerada (`algo.vercel.app`) no link da bio do Instagram.

Cada `git push` na `main` republica o site automaticamente.

## Onde editar

- Número e mensagem do WhatsApp: procure por `wa.me/5586998223532` em `index.html` (aparece 3 vezes).
- Textos: dentro de `<main>` em `index.html`.
- Cores: variáveis no começo do `<style>` (`--gold`, `--yellow`, `--bg`...).
- Foto: substitua `assets/rammyche.jpg` mantendo o nome.
