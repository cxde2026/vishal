# Vishal Dhinakar — Marketing Strategist Portfolio

A standalone static portfolio site for **Vishal Dhinakar**, a marketing strategist and growth specialist.

## Stack

Plain HTML, CSS and a tiny progressive-enhancement script. No build step, no framework — open `index.html` in a browser or serve the folder with any static host.

```
portfolio-vishal/
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Run locally

Serve this folder directly:

```bash
python3 -m http.server 5173
# visit http://localhost:5173
```

Or just double-click `index.html`.

## Deploy

Drop the folder onto any static host:
- **Vercel** – drag & drop or connect repo
- **Netlify** – drag & drop or connect repo
- **Cloudflare Pages** – connect repo
- **GitHub Pages** – push to `gh-pages` branch
- **Any static host** – FTP, S3, Heroku static buildpack, etc.

No configuration required. Single-file operation.

## Editing content

Edit `index.html` to update:
- Hero headline and tagline
- About section
- Work/projects
- Contact info

Edit `styles.css` to customize colors, fonts and layout.

Edit `script.js` for interactivity (currently handles smooth scroll and fade-in animations).
