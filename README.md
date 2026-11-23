# Sevinch Shavkatova — portfolio website

A responsive, static personal portfolio built with plain HTML, CSS, and JavaScript. No build step or dependencies are required.

## Preview locally

Open `index.html` in a browser. For local testing, you can also run `python -m http.server` from the project directory and visit `http://localhost:8000`.

## Add your portrait

The chat image itself is not available to the repository file writer, so the page currently displays a burgundy monogram placeholder. To use your portrait:

1. Add your original portrait to the repository at `assets/profile.jpg`.
2. The page automatically uses it and crops it into a circle. The fallback monogram remains available if the photo is missing.

## Publish with GitHub Pages

1. Open the repository **Settings** → **Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.
4. Wait for the deployment. Your site URL will appear on the Pages settings screen and is typically `https://shavkatovasevinch92-eng.github.io/sevinch-portfolio/`.

You can also deploy the repository directly with Netlify by importing it as a static site; no build command is needed and the publish directory is `.`.
