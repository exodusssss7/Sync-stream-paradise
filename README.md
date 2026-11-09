# SyncStream Paradise — Paradise Found Party

A simple, stable watch party. Create a room, share the code, and watch in sync with friends — no accounts, no fuss.

**Live demo:** https://syncstream-paradise.onrender.com

## Features

- **Create or join rooms** — pick a nickname, start a room, share the code
- **Host video uploads** — upload a local video file up to 4 GB, streamed to the room with range support
- **Paste a link instead** — direct video URLs work, and Google Drive / Dropbox share links are auto-converted to streamable URLs
- **Synchronized playback** — play, pause and seek stay in sync for everyone via Socket.IO
- **Live chat** — built into every room
- **Dark mode** — toggle in the UI

## Quick start

```bash
npm install
node server.js
```

The server listens on `PORT` (default `3000`). Open `http://localhost:3000`, enter a nickname, and create your first room.

No environment variables or API keys are required.

## Tech stack

- Node.js + Express 5
- Socket.IO for real-time sync and chat
- Multer for large file uploads
- Vanilla HTML/CSS/JS frontend (in `public/`)

## About this build

This repository is the **stable May 2026 build** of Paradise Found Party — the exact version that has been running in production since May 2026, preserved as-is.

## License

MIT — see [LICENSE](LICENSE).
