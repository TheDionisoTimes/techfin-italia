# TechFin Italia Blog

Blog statico generato con Hugo su finanza personale, tecnologia e attualità italiana.

## Struttura

- `content/posts/` — articoli in Markdown
- `config.toml` — configurazione Hugo
- `themes/mainroad/` — tema Mainroad
- `.github/workflows/hugo.yml` — auto-deploy su GitHub Pages

## Sviluppo locale

```bash
cd ~/passive_income_blog
hugo server -D  # -D include draft posts
```

## Aggiungere un articolo

```bash
hugo new posts/titolo-articolo.md
# edita il file in content/posts/
```

## Deploy

Push su `main` → GitHub Actions builda e pubblica su GitHub Pages automaticamente.