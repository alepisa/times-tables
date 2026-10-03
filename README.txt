TIMES TABLES VOICE QUIZ — PHONE PWA

This is an installable Progressive Web App (PWA).

IMPORTANT
The files must be hosted over HTTPS for normal phone microphone/PWA behavior.
Opening index.html directly from the phone's Files app is not equivalent.

DEPLOY
Upload all four files in this folder to any static HTTPS web host:
- index.html
- manifest.webmanifest
- sw.js
- icon.svg

ANDROID (Chrome)
1. Visit the HTTPS address.
2. Allow microphone access.
3. Open Chrome's menu.
4. Choose "Install app" or "Add to Home screen".
5. Launch Times Tables from the new home-screen icon.

IPHONE / IPAD (Safari)
1. Visit the HTTPS address in Safari.
2. Allow microphone access if requested.
3. Tap Share.
4. Choose "Add to Home Screen".
5. Launch it from the home-screen icon.

VOICE SUPPORT
The app uses the browser's Web Speech API. Support and behavior vary by
browser/OS. Chrome on Android is generally the best target for this version.
iOS browser speech-recognition support can be more restrictive.

The service worker caches the app shell for app-like loading, but speech
recognition itself may still require a network connection depending on the
phone/browser.
