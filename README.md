# Simple Starter Site

A lightweight, single-page website with a hero, feature highlights, and a launch checklist. Update the copy and links, then host the static files anywhere.

## Preview locally (no server needed)
Open `index.html` directly in your browser (double-click it or drag it into a tab). All assets are static and will load without any background services.

## Publish with GitHub Pages
Use GitHub Pages to serve the HTML and CSS directly from your repository:

1. Create a new repository and add `index.html` and `styles.css` to the root.
2. Commit and push the files to the `main` branch.
3. In **Settings → Pages**, set **Source** to `Deploy from a branch`, pick the `main` branch, and choose the `/ (root)` folder.
4. Click **Save**. GitHub will build the site and provide a public URL like `https://<username>.github.io/<repo>/`.

That URL will serve your static site—no custom server or additional setup required.

## One-click deploy via GitHub Actions (optional)
If you prefer GitHub Pages to deploy automatically after every push to `main`, keep the provided workflow:

1. Ensure the repository has **Pages → Build and deployment → Source** set to **GitHub Actions**.
2. Push your changes to `main`; the workflow at `.github/workflows/deploy.yml` will upload the root folder as a Pages artifact and publish it.
3. After the first successful run, GitHub will display the public URL in the workflow summary and on the **Pages** settings screen.

The workflow uses only static files—no custom server or build step is required.
