# PDF Dr — GitHub Pages

This folder contains the PDF Dr website prototype as `index.html`.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new **public** repository named `pdf-dr` (or another name you prefer).
2. Upload `index.html` and this `README.md` to the repository's root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for GitHub Pages to finish publishing. The Pages URL will be shown in **Settings → Pages**.

If the repository is named `yourusername.github.io`, GitHub can publish it at the root of your account domain. Otherwise, the URL usually includes the repository name.

## Important limitation
This is an interactive front-end prototype. The tool cards, search, categories, file selection and workflow dialogs work, but most PDF actions are not yet processing files or generating converted downloads. Real processing requires integrating suitable in-browser PDF libraries and/or a secure backend. GitHub Pages only hosts static files; it does not run server-side code.
