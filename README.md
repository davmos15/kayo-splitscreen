# Kayo SplitView Launcher

**Unlock SplitView on Kayo Sports for LG Smart TVs**

Kayo Sports disables SplitView (multi-stream viewing) on LG WebOS TV browsers by detecting the Smart TV user-agent. This tool spoofs a desktop Chrome user-agent so Kayo serves the full desktop player with SplitView enabled.

## [Launch the App](https://nadavmoskow.github.io/kayo-splitscreen/)

## How It Works

1. Your LG TV browser identifies as `Web0S; Linux/SmartTV` — Kayo detects this and blocks SplitView
2. This launcher opens Kayo inside a frame with a spoofed **Windows Chrome user-agent**
3. Kayo thinks you're on a desktop PC and serves the full player with SplitView
4. Click the SplitView icon (grid/+ icon) in the player controls to add a second stream

## Features

- **Auto-detection** — detects your browser environment (LG WebOS, Chromecast, Desktop) and shows relevant status
- **Iframe launch** — loads Kayo in a frame with spoofed UA for seamless TV experience
- **Direct open fallback** — opens Kayo in a new tab if iframe is blocked by CSP
- **UA test button** — verify the spoof is working via whatismybrowser.com
- **Remote-friendly** — keyboard navigation and LG Magic Remote back-button support
- **Android workaround** — step-by-step guide for screen mirroring SplitView from your phone

## Usage

### On LG TV (Primary Method)
1. Open the LG TV web browser
2. Navigate to the [hosted page](https://nadavmoskow.github.io/kayo-splitscreen/)
3. Click **"Launch Kayo with SplitView"**
4. If the iframe is blocked, use **"Open Kayo Directly"**

### Android Screen Mirror (Fallback)
1. Open Kayo on your Android phone and start a stream
2. Enable SplitView in the mobile app
3. Screen cast/mirror your phone to the LG TV
4. Kayo never detects a cast session, so SplitView stays active

## Limitations

- Kayo's Content Security Policy (CSP) may block the iframe method — the direct open and Android mirror methods are reliable fallbacks
- The UA spoof via `Object.defineProperty` only affects the current JavaScript context, not HTTP request headers
- Some streaming DRM may behave differently with a spoofed UA

## Support

If you found this useful, consider supporting the project:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/nadavmoskow)

## License

MIT
