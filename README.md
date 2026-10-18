# DLNAScreenStream V1.1

**Mirror your PC screen to any smart TV — zero config, low latency, crystal clear**

---

## What Is This?

DLNAScreenStream is a Windows desktop screen mirroring tool. It streams your computer screen in real time to any DLNA-compatible device on your local network — smart TVs, projectors, and media players.

No drivers to install. No router setup. Just double-click and go.

---

## Key Features

### 📺 Live Streaming

- **Real-time screen mirroring** — your desktop appears on the TV with sub-second latency
- **System audio sync** — PC audio output plays through the TV speakers
- **Multiple quality presets** — 720p / 1080p / native resolution, up to 60fps
- **Hardware-accelerated encoding** — auto-detects Intel QSV, NVIDIA NVENC, and AMD AMF
- **Branded intro** — 2-second logo animation at the start of each stream

### 🖼️ Slideshow Capture

- **Smart screenshot** — captures the screen on mouse clicks, scroll events, or key presses
- **Timed capture** — auto-captures every 0.5 seconds, ideal for slide presentations
- **In-memory storage** — screenshots are held in RAM, no files written to disk
- **One-click push** — send captured images directly to the TV

### 📱 DLNA Device Management

- **Auto-discovery** — scan and find all DLNA renderers on your network
- **Remote volume control** — adjust TV volume and mute from your PC
- **Multi-device support** — manage multiple TVs and projectors simultaneously

---

## Use Cases

| Scenario | Description |
|----------|-------------|
| **Meeting rooms** | Mirror your laptop to the conference room TV — no HDMI cable needed |
| **Classrooms** | Instructors share their screen with students on a big display |
| **Home entertainment** | Watch web videos or PC content on your living room TV |
| **Live monitoring** | Push your desktop to a TV as a reference/preview monitor |

---

## Why Use It?

- **Zero configuration** — auto-detects encoders and audio devices, works out of the box
- **Fully portable** — single executable, no installation, no registry entries, no leftovers
- **Broad compatibility** — HTTP-TS protocol works with the vast majority of smart TVs
- **Lightweight** — hardware encoding keeps CPU usage minimal
- **System tray** — minimize to tray, stays out of your way
- **Auto-start streaming** — begins pushing video as soon as the app launches

---

## System Requirements

- Windows 10 / 11 (64-bit)
- A DLNA-compatible TV or media player on the same network
- Hardware encoder recommended (Intel / NVIDIA / AMD discrete or integrated GPU)

---

## Quick Start

1. Double-click `DisplayNet V1.1.exe`
2. The app starts streaming automatically (status bar shows the stream URL and FPS)
3. Click **"Discover Devices"** to find your TV
4. Click **"Push"** next to a device — your screen appears on the TV

> Tip: The first few seconds may be slow while the encoder initializes. If the TV shows a black screen, the app will retry automatically.

---

## Technical Specifications

| Item | Value |
|------|-------|
| Streaming protocol | HTTP-TS (MPEG-TS over HTTP) |
| Video codec | H.264 (hardware acceleration supported) |
| Audio codec | AAC |
| Default frame rate | 24 fps |
| Default resolution | 1280×720 |
| Default port | 2000 |
| Screen capture | DXGI Desktop Duplication |
| Audio capture | WASAPI Loopback |

---

## Contact

For questions or support, email [gongxd@126.com](mailto:gongxd@126.com)
