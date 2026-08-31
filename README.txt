Premium Bonds Pots — v4 PWA

This version adds:
- Backup status and age indicator
- Installable PWA manifest and icons
- Offline service worker cache

Security model:
- No NS&I or bank credentials are stored.
- Financial tracker data remains in the browser's localStorage on the device where you use the app.
- Hosting these static files does not upload your balances or transactions.

For installability, serve the folder over HTTPS. Once hosted, open the site in Chrome on Android and choose Install app / Add to Home screen.
