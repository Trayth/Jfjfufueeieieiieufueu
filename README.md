# Pocket Arcade Menu

A self-contained HTML game hub built for quick play on mobile devices. The first game, **Mental Math Sprint**, is ready to go and everything—markup, styling (fully inline), and scripts—lives in a single file for easy sharing.

## Open it anywhere
- Download `index.html` to your phone, tablet, or desktop.
- Tap it from your Files app or drag it into your browser.
- No network connection or extra files are required after download.

## Publish with GitHub Pages
Serve the HTML directly from GitHub without a custom server:
1. Create a repository and add `index.html` to the root.
2. Commit and push to the `main` branch.
3. In **Settings → Pages**, choose **Deploy from a branch**, select `main`, and pick the `/ (root)` folder.
4. Save. GitHub will publish and provide a URL like `https://<username>.github.io/<repo>/`.

## Optional: auto-deploy via GitHub Actions
If you keep the provided workflow in `.github/workflows/deploy.yml`, set **Pages → Build and deployment → Source** to **GitHub Actions**. Every push to `main` will upload `index.html` (with all CSS embedded) and republish the site automatically.
