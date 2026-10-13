# Yozora Website

A lightweight static landing page for the Yozora browser project. It uses plain HTML and CSS, with no build step, package manager, or paid hosting.

## Preview locally

Open `index.html` in a browser. The only external requests are Google Fonts; the page remains usable with fallback fonts if they are unavailable.

## Publish with GitHub Pages

1. Create a GitHub repository named `yozora-website` and push this folder to its `main` branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions**.
4. The workflow in `.github/workflows/pages.yml` deploys the site on pushes to `main`. Check the **Actions** tab for the first deployment; the published URL appears in the Pages settings.

GitHub Pages is free for public repositories. No paid hosting or framework is required.

## Before publishing

The browser repository link in `index.html` points to [Inazuma-dev/Yozora](https://github.com/Inazuma-dev/Yozora). The Yozora logo is stored locally at `assets/yozora-logo.jpg`. Social links in the footer point to [X](https://x.com/Inazuma_dev) and [GitHub](https://github.com/Inazuma-dev).
