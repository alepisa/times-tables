Times Tables PWA v5 — iPhone startup fix

Fixes the 'undefined times undefined' problem:
- The first multiplication question is generated before question audio starts.
- The Repeat button cannot speak until a valid question exists.
- Removes the greeting/question timing race seen on iOS.
- New service-worker cache version forces the updated app files to replace v4.

Upload index.html, manifest.webmanifest, sw.js and icon.svg to GitHub Pages.
After deployment, refresh the Safari page once, close the Home Screen app completely,
then reopen it.
