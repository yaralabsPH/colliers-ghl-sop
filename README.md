# Colliers Catering — SOPs

Internal operations documentation, published as static pages.

## Pages

- `index.html` — SOP index (start here)
- `colliers-catering-enquiry-sop.html` — "Get my quote" form enquiry SOP
- `colliers-catering-chat-widget-sop.html` — Chat widget enquiry SOP
- `colliers-catering-flex-ghl-integration.html` — Flex → GHL integration reference

## Deploying with GitHub Pages

1. Create a new GitHub repo (public, or private if you're on a paid plan — Pages needs public on the free tier).
2. Push everything in this folder to the repo root (see commands below).
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main, folder: / (root)** → Save.
4. GitHub gives you a URL like `https://<username>.github.io/<repo-name>/` — that's your live site, index.html loads automatically.

```bash
cd path/to/this/folder
git init
git add .
git commit -m "Initial SOP site"
git branch -M main
git remote add origin https://github.com/<username>/<repo-name>.git
git push -u origin main
```

Pages usually goes live within a minute or two of the first push, and re-deploys automatically on every push to `main` after that.
