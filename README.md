# Emillio Kuria Wairimu — Portfolio Website

A responsive single-page portfolio built with HTML, CSS, and vanilla JavaScript.

## Run locally in VS Code
1. Extract this ZIP to a folder.
2. Open VS Code → **File → Open Folder...** → choose `emillio-portfolio`.
3. Install the **Live Server** extension by Ritwick Dey (optional but convenient).
4. Right-click `index.html` → **Open with Live Server**. Or open `index.html` directly in a browser.

## Replace the portrait
1. Prepare a professional head-and-shoulders photo, ideally JPG or WebP.
2. Copy it into the `assets` folder, for example `assets/emillio.jpg`.
3. In `index.html`, find:
   `<img src="assets/profile-placeholder.svg" ...>`
4. Change the source to:
   `<img src="assets/emillio.jpg" alt="Emillio Kuria Wairimu">`

Use a photo you have permission to publish. Keep the `alt` text meaningful.

## Personalize before publishing
- Verify the dates, project descriptions, and the 98%+ quality approval claim against your records.
- Add real LinkedIn and GitHub URLs when ready. Do not publish placeholder or invented links.
- Add live project links only where the project is actually accessible.
- The contact phone and email are taken from the supplied CV; change them if you prefer different public contact details.
- Add a PDF CV file in `assets/` and link a button to it if desired.
- The current site does not generate a QR code; make one after deployment using the final HTTPS URL.

## Publish
### GitHub Pages (static website)
1. Create a GitHub repository, e.g. `emillio-portfolio`.
2. Upload the files and folders in this project to the repository root.
3. In the repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for the deployment URL. Test the site on phone and desktop.

The site uses Google Fonts from a CDN. If you prefer no third-party font request, remove the Google Fonts `<link>` elements from `index.html`; system fallback fonts will be used.

## Accessibility / quality checks
- Keyboard-test the menu and all links.
- Test at mobile widths and zoom to 200%.
- Ensure text contrast and photo alt text remain meaningful.
- Check all public contact details before sharing.
