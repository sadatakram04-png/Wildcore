# WILDCORE V1 — iPhone PWA starter

## Included
- Arabic-first dark tactical interface
- Home dashboard
- 3-day forest training plan
- Water tracker (manual)
- Weight and recovery check-in
- Local device storage using localStorage
- PWA manifest, service worker, app icons

## Important limitations
- This starter does not include an AI model, GPS tracking, cloud sync, Apple HealthKit, accounts, push notifications, or medical recommendations.
- Data is stored locally in the browser on this device. Clearing Safari website data can remove it.
- For iPhone installation, the site must be hosted over HTTPS. The service worker requires HTTPS (localhost is an exception).

## Deploy using Replit on iPhone
1. Open https://replit.com/ in Safari and sign in/create an account.
2. Create a new project. Choose a static website / HTML, CSS, JS template if available.
3. Upload the files from this ZIP into the project root: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.
4. The service-worker registration is already included in index.html.
5. Use Replit's Run/Publish/Deploy flow for a static website and obtain its HTTPS public URL. Availability and free limits may change.
6. Open the HTTPS URL in Safari on iPhone.
7. Tap Share → Add to Home Screen → Add.
8. Launch WILDCORE from the new Home Screen icon.

## Local preview
Open index.html in a browser for a basic preview. PWA install/offline features require HTTPS hosting.
