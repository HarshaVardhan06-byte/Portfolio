# Harsha Vardhan R — Developer Portfolio

A responsive, single-page portfolio built with plain HTML, CSS, and JavaScript. Includes a 3D-inspired hero, layered motion effects, interactive project case studies, theme toggle, responsive navigation, résumé download, GitHub QR code, and contact links. Five selected projects are included, with RescuPath AI featured first.

## Preview locally
Open `index.html` in Chrome, Edge, or Firefox. No Node.js, package installation, build step, or VS Code is required. Keep `index.html` and the `assets/` directory together.

## Contact-link behavior
- **Let's Connect** scrolls to the contact section.
- **Call now** uses the standard `tel:+916362433439` link. On a phone this opens the dialer; on a desktop the result depends on whether an app is registered to handle `tel:` links.
- Email opens the visitor's configured email application.

## Publish to GitHub
1. Create a new empty GitHub repository named `harsha-portfolio` under `HarshaVardhan06-byte` at https://github.com/new. Do not initialize it with a README.
2. Open a terminal in this extracted `Harsha_Portfolio_Website` folder and run:

```bash
git init
git add index.html assets README.md vercel.json .gitignore
git commit -m "Add responsive developer portfolio"
git branch -M main
git remote add origin https://github.com/HarshaVardhan06-byte/harsha-portfolio.git
git push -u origin main
```

If `origin` already exists, run `git remote set-url origin https://github.com/HarshaVardhan06-byte/harsha-portfolio.git` and repeat the push. Never put secrets or `.env` files in this static website repository.

## Deploy to Vercel using the website
1. Open https://vercel.com/new and import `HarshaVardhan06-byte/harsha-portfolio`.
2. Set **Framework Preset** to **Other**, **Root Directory** to `./`, leave **Build Command** blank, and set **Output Directory** to `.`.
3. Click **Deploy**. Later pushes to `main` should trigger new deployments automatically.

Alternatively, GitHub Pages can host it: open repository **Settings → Pages → Deploy from a branch → main → /(root)** and save.
