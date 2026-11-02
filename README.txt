ALLOTMENT BUDGET - install on your phone
========================================

This folder is a complete app. It has to be on a website (https) before your
phone can install it. Free hosting takes about five minutes:

OPTION A - Netlify (easiest)
1. On a computer, go to app.netlify.com/drop and sign up for a free account.
2. Unzip this file and drag the whole "allotment-app" folder onto the page.
3. Netlify gives you a link like https://something.netlify.app
   (you can rename it in Site settings).

OPTION B - GitHub Pages
1. Create a free GitHub account and a new public repository.
2. Upload the files inside "allotment-app" (index.html, sw.js, etc.).
3. Settings > Pages > Deploy from branch > main > Save.

INSTALL IT
- iPhone: open the link in Safari > Share button > Add to Home Screen.
- Android: open the link in Chrome > three-dot menu > Install app
  (or Add to Home screen).

After the first open it works offline. Your budget is saved on the phone only.

BRING YOUR DATA OVER
In the Claude version: Accounts > Export backup. Then in the phone app:
Accounts > Import backup and pick that file.

KEEP BACKUPS
Deleting the app or clearing Safari/Chrome website data erases the budget.
Use Accounts > Export backup now and then and keep the file somewhere safe.

UPDATING THE APP LATER
Replace the files on your host, and change VERSION at the top of sw.js
(e.g. allotment-v2) so phones pick up the new version.
