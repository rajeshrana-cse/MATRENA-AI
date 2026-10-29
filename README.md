# Materna AI

A static, single-page maternal wellness website prototype.

## Files

- `index.html` — the complete website. CSS, JavaScript, and illustration images are embedded in this file.
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing.
- `DEBUG_REPORT.md` — basic checks performed on this copy.

## Deploy with GitHub Pages

1. Create or open your GitHub repository.
2. Upload **the files inside this folder** to the repository's top level. Make sure `index.html` is at the root, not nested inside another folder.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose branch `main` and folder `/ (root)`, then click **Save**.
7. Wait for GitHub Pages to finish deploying, then open the URL shown in Settings → Pages.

## Important prototype notes

- The app is front-end only. Login currently asks for a name and opens the app; it does not create a secure account.
- Health data and interactions are not connected to a server or medical record system.
- The chatbot and some actions are demonstration features.
- Do not use this prototype as a substitute for professional medical advice.

## If GitHub Pages still shows an error

Check that `index.html` is in the repository root and Pages is configured for `main` + `/(root)`. If a page loads but displays a blank screen, open browser Developer Tools → Console and share the first red error message. If GitHub shows a deployment/build error, copy the exact message from the Actions tab.
