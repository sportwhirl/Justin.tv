# justin.tv

A responsive, static live-stream discovery page ready for GitHub Pages. The stream tiles and viewer counts are sample content. Search and category filters work in the browser; sign-in and streaming buttons are demo actions because GitHub Pages does not provide a streaming backend.

## Deploy

This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml`. Push to the `main` branch, then in the repository open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source. The workflow publishes the root of the repository on each push to `main`.

GitHub Pages serves the project under a `github.io` address. Using `justin.tv` as a custom domain requires control of that domain and a DNS configuration.
