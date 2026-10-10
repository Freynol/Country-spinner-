COUNTRY SPIN — ANDROID PWA PACKAGE

Included:
- index.html: the Country Spin app
- manifest.webmanifest: app name, icon and full-screen display preference
- sw.js: service worker for offline use
- icons/: Android launcher icons

IMPORTANT:
A Progressive Web App must be hosted on HTTPS (or localhost) to be installable. Opening index.html directly from Downloads will let you test the page, but will not enable PWA installation or offline caching.

EASIEST INSTALL PATH:
1. Upload the contents of this folder to a static HTTPS host such as GitHub Pages or Netlify.
2. Open the resulting HTTPS URL in Chrome on Android.
3. Open Chrome's ⋮ menu and choose "Install app" (or "Add to Home screen", depending on the menu).
4. Launch Country Spin from the new home-screen icon. The manifest requests fullscreen display; Android/browser behavior can vary by device.

This package is a PWA, not a signed APK. A native APK would require an Android project/build process.
