TIMES TABLES TURBO v6

Upload ALL files in this folder to the root of your existing GitHub Pages repository.

Features:
- 60-second game sessions
- Correct-answer score
- Current and best streak
- End-of-game score screen
- Best Today top 5
- All-Time top 5
- 1990s arcade-inspired visual treatment
- PWA / Add to Home Screen support
- Voice questions and spoken feedback

CURRENT LEADERBOARD:
This ZIP works immediately and stores scores in localStorage, so Today's and All-Time
leaderboards are for the current device/browser. This avoids requiring database credentials.

SHARED LEADERBOARD:
config.js is reserved for the next step. A truly shared leaderboard across phones needs
a hosted database/backend. Do not put private database passwords in GitHub Pages files.

After uploading, wait for GitHub Pages to deploy, refresh in Safari, then fully close and
reopen the installed Home Screen app so the new service worker takes over.
