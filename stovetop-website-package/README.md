# Stovetop Static Website Package

This package contains a simple static website for App Store submission and user support.

## Files
- `index.html` — support page
- `privacy.html` — privacy policy page
- `styles.css` — shared styling

## Publish on GitHub Pages
1. Create a new **public** GitHub repository.
2. Upload these files to the root of the repo.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Save.
6. Your site will be available at:
   `https://YOUR_USERNAME.github.io/REPO_NAME/`

## App Store URLs
Use these URLs in App Store Connect:
- Support URL: `https://YOUR_USERNAME.github.io/REPO_NAME/`
- Privacy Policy URL: `https://YOUR_USERNAME.github.io/REPO_NAME/privacy.html`

## Important customizations before publishing
Replace these placeholders:
- `support@stovetopapp.com` with your real support email
- `Stovetop` / legal business information if needed
- Any privacy policy language so it matches your actual data practices

## Notes
This is a static site. No backend or hosting fees are required when using GitHub Pages with a public repository.
