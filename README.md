# fomo-desk-app

Public, static phone UI for the Grok Bot desk. Hosted on GitHub Pages from the `main` branch root.

This repository is a **frontend-only** placeholder. It must never contain the privileged database key, `settings.seed.json`, logs, trading data, or any other files from the desk process.

Local clone on the bot's computer: `/workspace/desk/web-repo`  
(The desk process itself lives in `/workspace/desk`; do not make that folder the git root.)

`config.js` holds the project URL and the **publishable / anon** key only (safe for a public website). Writes to the database use a secret key on the box, stored outside git, not in this repo.
