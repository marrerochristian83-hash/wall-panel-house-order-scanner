WALL PANEL HOUSE ORDER SCANNER — SHAREABLE WEB APP

This folder is a Progressive Web App (PWA). Once hosted on HTTPS, people can open the link and use “Add to Home Screen” / “Install App” to save it like an app.

FREE HOSTING OPTION: GITHUB PAGES
1. Create a free GitHub account.
2. Create a new public repository, e.g. wall-panel-house-order-scanner.
3. Upload ALL files from this folder.
4. In the repository: Settings -> Pages -> Deploy from branch -> main -> / (root) -> Save.
5. GitHub will give you an HTTPS website address.
6. Share that one address with your coworkers.
7. On iPhone Safari: open the link -> Share -> Add to Home Screen.
8. On supported browsers, use Install App / Add to Home Screen.

Important:
- The app currently uses browser OCR (Tesseract.js loaded from a CDN), so the first scan needs internet access to load the OCR library.
- The app's service worker caches the app shell after first load.
- The current component rules are the supplied internal fence cheat sheet. Verify pull lists before pulling material.
- A production version should move the AI/OCR extraction to a controlled backend and add login/permissions if the company wants private orders.
