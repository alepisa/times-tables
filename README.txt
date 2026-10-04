TIMES TABLES v8 — MINIMAL

This version deliberately removes the decorative arcade layers that could interfere
with the name input. The name field is now a plain native HTML text input with no
overlays or special touch handlers.

Changes:
- Minimal black/white design
- Monospace/pixel-like retro typography only
- Removed "Turbo" everywhere
- Rebuilt name-entry screen from scratch
- 60-second sessions retained
- Current streak and best streak retained
- Best Today and All Time local leaderboards retained
- Green correct / red wrong feedback retained
- Voice questions and spoken corrections retained
- New service worker cache: times-tables-v8

GITHUB PAGES UPDATE:
Replace the old repository files with index.html, manifest.webmanifest, sw.js and icon.svg.
After GitHub Pages redeploys, refresh the website in Safari/Chrome. If an old installed PWA
is still cached, remove the old Home Screen app, open the GitHub Pages URL in Safari again,
then Add to Home Screen again.
