# A Round Calculator — Android + iPhone

This is a ready-to-host Progressive Web App (PWA) made from the supplied HTML calculator. It can be installed on **Android and iPhone** from a supported browser and runs like an app without needing an app store.

## Install on a phone
1. Put the contents of `www/` on an HTTPS website.
2. Open the website on the phone.
3. Android: use the browser's **Add to Home screen / Install app** option.
4. iPhone: in Safari, use **Share → Add to Home Screen**.

## Native store versions
The same `www/index.html` can also be wrapped with Capacitor for Google Play and Apple App Store builds. Building/signing the native packages requires Android Studio for Android and Xcode on macOS for iPhone.

## Included
- `www/index.html` — calculator
- `www/manifest.webmanifest` — installable-app metadata
- `www/sw.js` — offline caching
- `www/icon-192.png` and `www/icon-512.png` — app icons

The original calculator features are preserved, including arithmetic, keyboard input, color customization, preset palettes, and reset-to-default colors.
