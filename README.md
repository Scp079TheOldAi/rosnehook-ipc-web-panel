# Rosnehook IPC Web Panel

Web dashboard for monitoring and controlling Rosnehook bot instances over IPC.

## Features

- Live bot status, stats, and in-game info
- Per-bot and fleet-wide commands
- Restart / terminate controls and bot quota
- Auto-restart for unresponsive IPC clients

## Setup

```bash
npm install
npm run build
./run.sh
```

Open the panel in your browser. Use the API password printed in the server console to log in.

## Development

```bash
npm run watch
```

Rebuilds `public/bundle.js` when `script.js` changes.

## Maintainer

[Scp079TheOldAi](https://github.com/Scp079TheOldAi) · 202x