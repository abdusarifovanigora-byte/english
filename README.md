# Morrow English

A personal English-learning PWA for the B1+ → B2 path. It is a static app: no account, server, paid service, or third-party JavaScript library is required. Your reading position, vocabulary, notes, completed grammar practice, and learning log are stored in this browser's local storage.

## Open it

For a quick look, open `index.html` in a modern browser. Local storage works; service-worker/offline installation requires serving the folder over `localhost` or HTTPS.

To serve locally with Python installed:

```powershell
py -m http.server 8000
```

Then open http://localhost:8000. In Safari on iPad, use **Share → Add to Home Screen**. The same localhost/HTTPS requirement applies; an HTTPS-hosted copy can be installed directly from Safari. The app shell is cached for offline use after the first successful load.

## Included

- Overview with the learner path and quick links
- Original, resumeable reading: “A Different Kind of Education”
- Vocabulary cards with add, review, and remove actions
- Grammar topics with examples and short practice prompts
- Progress log with optional quiz score; no historical stats are prefilled
- Private notes that save as you type

## Data and typography

App data stays in this browser unless you clear its site data. A system serif/sans-serif fallback is included. When online, DM Serif Display and DM Sans may load from Google Fonts; the app remains usable without them.
