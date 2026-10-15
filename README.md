# Shouji Diannao

Shouji Diannao keeps your notes in sync between your phone and your computer —
convenient, fast, and secure. Your notes stay consistent across devices in real
time, with no third-party cloud drive and no complex configuration.

## Features

- **Convenient** — Pair devices with a one-time dynamic code. Enter the code
  once on a new device to pair it; after that, syncing runs automatically with
  no repeated sign-in.
- **Fast** — Multiple data centers across mainland China. The client
  automatically connects to the lowest-latency data center, so domestic access
  needs no VPN.
- **Secure** — Notes are protected with elliptic-curve key exchange and AES
  encryption. The keys never leave your devices, so the server cannot read your
  note content.

## Installation

### Manual installation

1. Download `main.js`, `manifest.json` and `styles.css` from the latest
   [Release](https://github.com/absyw/shoujidiannao/releases).
2. In your vault, create the folder
   `<your-vault>/.obsidian/plugins/shoujidiannao-absyw/`.
3. Place the three downloaded files into that folder.
4. Restart Obsidian, open **Settings → Community plugins**, and enable
   **Shouji-Diannao** in the installed plugins list.

## Usage

1. After enabling the plugin, open its settings page.
2. **First device**: sign in to create your sync library automatically.
3. **Additional devices**: generate a dynamic code on an already-paired device,
   then enter that code on the new device to pair it.
4. Once paired, the plugin starts syncing automatically; note changes then
   propagate between devices in real time.

## Network use and accounts

- Syncing requires an account on the Shouji Diannao sync service. Note content
  is end-to-end encrypted before it leaves your device.
- The plugin connects to the sync service (`notebooksyncer.com`,
  `bijitongbu.site`, `bijitongbu.cn`) to sync your vault and to check for plugin updates.
- A free storage tier is available; larger storage requires a paid plan.
- No telemetry or analytics are collected.

## Compatibility

- Requires Obsidian `1.4.0` or higher.
- Works on desktop and mobile.

## License

[MIT](./LICENSE)
