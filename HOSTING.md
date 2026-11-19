# Hosting Lord Pharaoh for free

All files in this folder are the whole game. Host them over HTTPS (needed for Install and offline play). Saves stay in each player's own browser.

**Netlify Drop:** 1) Open https://app.netlify.com/drop  2) Drag this `pwa` folder (or unzip `pharaoh-pwa.zip` and drag it) onto the page  3) Open the https link it gives you on your phone and tap **Install App** (Android) or **Share > Add to Home Screen** (iPhone).

**GitHub Pages:** 1) Create a public repo and upload the contents of this folder to the root  2) Settings > Pages > Deploy from branch `main`, folder `/ (root)`  3) Open `https://<you>.github.io/<repo>/` on your phone and install it.

**Cloudflare Pages:** 1) dash.cloudflare.com > Workers & Pages > Create > Pages > Upload assets  2) Name the project and upload this folder  3) Open the `https://<project>.pages.dev` link on your phone and install it.

After an update, upload all files again; the service worker version changes automatically and players get the new version on their next launch (or the one after).
