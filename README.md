# Kayo SplitView Launcher

**Get SplitView working on your Smart TV — auto-detects your device and shows the best workaround**

Kayo Sports blocks SplitView on all Smart TVs, Chromecast, AirPlay, PlayStation, and Fire TV. This page detects your TV and gives you step-by-step instructions to get SplitView working anyway.

## [Use the App](https://davmos15.github.io/kayo-splitscreen/)

## Supported TVs

The app auto-detects these platforms and provides tailored recommendations:

| TV / Device | Detected Via | Kayo App | SplitView | Workarounds |
|---|---|---|---|---|
| **LG (WebOS)** | `Web0S`, `webOS` | Yes | Blocked | UA spoof launcher, screen mirror, HDMI |
| **Samsung (Tizen)** | `Tizen`, `SMART-TV` | Yes | Blocked | Screen mirror, HDMI |
| **Hisense (VIDAA)** | `VIDAA`, `Model/Hisense` | Some models | Blocked | AnyView Cast mirror, HDMI |
| **Sony (Android TV)** | `BRAVIA`, `SonyDTV` | Yes | Blocked | Chromecast built-in mirror, HDMI |
| **Panasonic** | `Panasonic`, `VIERA` | No | N/A | Miracast mirror, HDMI |
| **Vizio (SmartCast)** | `VIZIO`, `SmartCast` | No | N/A | AirPlay 2 mirror, HDMI |
| **Philips** | `Philips`, `NETTV`, `Saphi` | Android TV only | Blocked | Screen mirror, HDMI |
| **Sharp (Aquos)** | `AQUOS` | No | N/A | Miracast mirror, HDMI |
| **Amazon Fire TV** | `AFT`, `Silk` | Yes | Blocked | Display mirroring, HDMI |
| **Android TV / Google TV** | Android + TV identifiers | Yes | Some devices | Chromecast built-in mirror, HDMI |
| **Chromecast (casting)** | `CrKey` | Cast only | Blocked | Phone screen mirror instead |
| **PlayStation** | `PlayStation` | Yes | Blocked | HDMI laptop |
| **Desktop browser** | (default) | Web | Works | No workaround needed |

## Workaround Methods

### 1. Android Screen Mirror (best for most TVs)
Enable SplitView in the Kayo phone app, then screen mirror to your TV. Kayo can't detect mirroring, so SplitView stays active. Each TV brand has its own mirroring feature (Screen Share, AnyView Cast, Smart View, etc.) — the app shows the correct steps for your TV.

### 2. Laptop + HDMI (guaranteed, any TV)
Connect a laptop via HDMI, open kayosports.com.au in Chrome. Full SplitView with up to 4 streams.

### 3. Apple TV 4K via HDMI (best dedicated device)
The only streaming device where Kayo SplitView works natively.

### 4. LG WebOS UA Spoof (LG only)
The launcher spoofs a desktop Chrome user-agent in the LG TV's built-in browser.

## Close Button Fix
The close button (for the iframe player) is positioned at the bottom-left to avoid overlapping Kayo's sign-in and player controls. It auto-hides after 4 seconds of inactivity and reappears on any mouse, keyboard, or touch input.

## Support

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/nadavmoskow)

## License

MIT
