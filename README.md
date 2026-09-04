# Colliers Catering - SOPs

Internal operations documentation, published as static pages.

## Pages

- `index.html` - SOP index (start here)
- `colliers-catering-enquiry-sop.html` - "Get my quote" form enquiry SOP
- `colliers-catering-chat-widget-sop.html` - Chat widget enquiry SOP
- `colliers-catering-flex-ghl-integration.html` - Flex to GHL integration reference
- `free-tasting-booking-sop.html` - Free Tasting booking link written SOP
- `free-tasting-booking-video.html` - Free Tasting booking link video tutorial
- `free-tasting-experience-email-notifications-sop.html` - Free Tasting experience and email notifications written SOP
- `free-tasting-experience-email-notifications-video.html` - Free Tasting experience and email notifications video tutorial
- `find-inactive-customers-sop.html` - Find inactive customers written SOP
- `find-inactive-customers-video.html` - Find inactive customers video tutorial

## Deploying with GitHub Pages

1. Create a new GitHub repo.
2. Push everything in this folder to the repo root.
3. In the repo: Settings > Pages > Build and deployment > Source: Deploy from a branch > Branch: main, folder: / (root) > Save.
4. GitHub gives you a URL like `https://<username>.github.io/<repo-name>/`.

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