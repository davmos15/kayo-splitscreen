# Kayo SplitView Launcher

**Get SplitView working on your Smart TV — LG, Hisense, Samsung & more**

Kayo Sports blocks SplitView (multi-stream viewing) on Smart TVs. This page provides a UA-spoof launcher for LG WebOS TVs and step-by-step workaround guides for every other TV.

## [Use the App](https://davmos15.github.io/kayo-splitscreen/)

## Supported TVs

| TV | What works |
|---|---|
| **LG (WebOS)** | UA-spoof launcher via built-in browser, or Android screen mirror |
| **Hisense (VIDAA)** | Laptop + HDMI, Apple TV / Chromecast via HDMI, or Android screen mirror via AnyView Cast |
| **Samsung (Tizen)** | Laptop + HDMI, streaming device via HDMI, or Android screen mirror |
| **Any TV with HDMI** | Plug in a laptop and use Kayo's web player in Chrome — full SplitView, no tricks |

## Workaround Methods

### 1. Laptop + HDMI (any TV, guaranteed)
Connect a laptop via HDMI, open kayosports.com.au in Chrome, and use SplitView directly. Up to 4 streams.

### 2. LG WebOS Browser Launcher
Open this page on the LG TV's built-in browser and click "Launch Kayo with SplitView". The tool spoofs a desktop Chrome user-agent so Kayo serves the full player.

### 3. Streaming Device via HDMI
Plug in an **Apple TV 4K** or **Chromecast with Google TV** — Kayo's app on these devices supports SplitView natively.

### 4. Android Screen Mirror (any TV)
Enable SplitView in the Kayo phone app, then screen mirror to your TV. Kayo never detects a cast session, so SplitView stays active. Works with Miracast, AnyView Cast (Hisense), Screen Share (LG), and Smart View (Samsung).

## Features

- **Auto-detection** — identifies your TV type (LG, Hisense, Samsung, Chromecast, Desktop) and shows relevant guidance
- **UA-spoof launcher** — iframe + direct-open methods for LG WebOS browsers
- **TV-specific guides** — clear step-by-step instructions for each TV brand
- **Remote-friendly** — keyboard nav and LG Magic Remote back-button support

## Limitations

- The iframe method may be blocked by Kayo's CSP — use "Open Kayo Directly" or another method
- The UA spoof only affects JavaScript context, not HTTP request headers
- Hisense VIDAA (older models like the P4 series) has no Kayo app and its browser can't run Kayo's web player

## Support

If this helped you watch the footy, consider buying me a coffee:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/nadavmoskow)

## License

MIT
