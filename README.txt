Times Tables PWA v3

NEW:
- Asks the player's name before starting.
- Requests microphone access before the quiz starts.
- Shows current consecutive-correct streak.
- Shows best streak.
- Best streak is stored separately for each player name on that device/browser.
- A wrong answer resets the current streak to zero.
- Existing voice questions, full-screen colors, spoken praise/corrections and listening watchdog remain.

Upload all files to your GitHub Pages repository, replacing the old files.
Because a service worker may cache an older version, reload the site after deployment.
On iPhone you may need to close/reopen the Home Screen app after GitHub Pages updates.

NOTE: The app requests getUserMedia microphone access once up front and keeps that stream open.
Safari/iOS may still separately control permission for its browser speech-recognition feature.
