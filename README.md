# Daryl Tautjo - Personal Portfolio

This is a static, single-page portfolio. The deployment entry point is `index.html`; Tailwind CSS is compiled at build time, and the site has no server or configured form backend.

## Run locally

Install the development dependency and compile the stylesheet:

```sh
npm ci
npm run build
```

Then open `index.html` in a browser or serve the project folder with any static HTTP server. Google Fonts, Material Symbols, and Three.js are loaded from their public CDNs, so those enhancements require an internet connection.

The contact form validates its fields and opens the visitor's email app with a prefilled message. It does not transmit or store form data.

## Deploy

- **GitHub Pages:** Push the repository, then select the `main` branch and `/ (root)` as the Pages source in repository settings.
- **Vercel:** Import the repository and select **Other**. Use `npm run build` as the build command and `dist` as the output directory.
- **Render:** Create a Blueprint from this repository. [`render.yaml`](./render.yaml) installs dependencies, builds the stylesheet, and publishes the clean `dist` folder as a static site.

## Push to GitHub

```sh
git init
git add .
git commit -m "Prepare responsive personal portfolio"
git branch -M main
git remote add origin <your-github-repository-url>
git push -u origin main
```

Commit the generated root `styles.css` with the source so GitHub Pages can serve it directly. Rebuild it with `npm run build` after changing Tailwind classes or configuration; the build also copies only `index.html` and `styles.css` into `dist/` for Vercel and Render. `.gitignore` excludes generated build folders, dependency folders, and local environment files. This site currently needs no environment variables.
