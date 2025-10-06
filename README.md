# Responsible AutoML Summer School Website

Static website for the II Advanced Summer School on Responsible AutoML.

## Local preview

Open `index.html` in your browser or serve the folder with any static server (for example, `npx serve .`).

## Deploying to GitHub Pages

1. Push the contents of this repository to your `main` branch.
2. Ensure GitHub Pages is configured to deploy from **GitHub Actions** in the repository settings.
3. Each push to `main` triggers the `Deploy static site` workflow (`.github/workflows/deploy.yml`) that uploads the site to GitHub Pages.

The `.nojekyll` file disables Jekyll processing so that assets are served exactly as provided.
