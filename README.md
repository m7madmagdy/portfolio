# Mohamed Magdy — Portfolio

Static portfolio ready for GitHub Pages. The navigation logo is **MM.**

## Files

- `index.html`: complete HTML, CSS, and JavaScript.
- `portrait.png`: profile photo.
- `.nojekyll`: serves the site as plain static files.

No package installation or build command is needed. Google Fonts is loaded online; system fonts are used as a fallback.

## Publish

1. Create a public GitHub repository named `m7madmagdy.github.io` for your main personal site, or use another repository name for a project site.
2. Upload the extracted files to the repository root, with `index.html` at the top level. Upload the files, not the ZIP or its enclosing folder.
3. Commit to the `main` branch.
4. Open **Settings → Pages**.
5. Select **Deploy from a branch**, choose **main** and **/(root)**, then save.
6. Wait for the Pages deployment to finish. GitHub displays the published URL in Pages settings.

Assets use relative paths, so this also works under a project repository URL.

Publishing source documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Customize

Edit the content and styling in `index.html`. Replace `portrait.png` to update the photo. Project filter buttons and the footer year use a small inline script.

The site includes your public email address and social profile links. Contact buttons use `mailto:`; no backend is required.

No custom domain is configured in this package. Add one later through GitHub Pages settings after registering it and configuring DNS.
