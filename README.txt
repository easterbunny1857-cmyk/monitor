WealthLab Portfolio - install as an app on iPhone / iPad

1. Put ALL files from this folder on any HTTPS web host (files must sit together in one folder):
   index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png
   Free options: GitHub Pages, Cloudflare Pages, Netlify.
2. Open the site's address in Safari (not inside another app).
3. Tap Share > Add to Home Screen > Add.
4. Open it once while online. After that it opens offline from the home screen icon.

Your data is stored on the device, inside the app. Use Export CSV regularly as a backup.
To ship an update, replace index.html on the host and change the version in sw.js (wealthlab-v1 -> wealthlab-v2).
