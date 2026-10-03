# Deploying SD Interiors to GitHub Pages

1. Create a GitHub repository and upload the contents of this folder to its `main` branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment → Source**, select **GitHub Actions**.
4. Open **Actions** and wait for `Deploy React app to GitHub Pages` to finish.
5. Your site will be available at `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

The app uses `HashRouter`, so routes such as `#/about` and `#/projects/1` work correctly on GitHub Pages.
