## DF Revestimentos — Landing Page

Landing page estática (HTML/CSS) focada em **DF Revestimentos em tecidos**:

- Revestimento em tecidos tensionados
- Backdrop
- Instagramáveis

### Estrutura

```txt
df-revestimentos-site/
├── index.html
├── styles.css
├── netlify.toml
├── README.md
└── assets/
    ├── logo.png
    ├── hero.webp
    └── gallery/
```

### Rodar localmente

- Abra `index.html` no navegador, ou
- Sirva a pasta com qualquer servidor estático.

Exemplo:

```bash
python3 -m http.server 5173
```

Depois acesse `http://localhost:5173`.

### Deploy (Netlify)

O `netlify.toml` publica a raiz do projeto (site estático).

### Observações de SEO

- Metatags básicas (title/description/OG/Twitter) ficam em `index.html`.
- O JSON-LD (`LocalBusiness`) está embutido e pode ser enriquecido com `url`/redes sociais quando disponível.

