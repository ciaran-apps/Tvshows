# TV Shows

Track TV rewatches: every episode with its title and runtime, how many days each rewatch took, a watch log and your rewatch history.

Live at **https://tvshows.ciarandevine.uk** — open it in Chrome and choose **Install app**.

- `index.html` — the whole app
- `cloud.js` — shared sign-in and sync with the `ciaran-apps` Firebase project (data at `users/<uid>/tvshows/`)
- `sw.js`, `manifest.json`, icons — make it installable and usable offline
- `CNAME` — the custom address for GitHub Pages

Signed out, everything is saved in the browser only. Use **Stats → Backup** to copy, download or import a backup.
