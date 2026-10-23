<div align="center">

<img src="assets/logo.png" alt="Qurani Logo" width="80" height="80">

# Qurani

**Your Quran, Your Way**

A clean, distraction-free Quran reader with beautiful Arabic typography, multi-translation support, and offline access.

[![Release](https://img.shields.io/github/v/release/qurani-app/qurani?color=3B82F6&style=flat-square)](https://github.com/qurani-app/qurani/releases)
[![License](https://img.shields.io/github/license/qurani-app/qurani?color=3B82F6&style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Android-3B82F6?style=flat-square)](https://github.com/qurani-app/qurani/releases)

[Download](#download) · [Features](#features) · [Build from Source](#build-from-source) · [Contributing](#contributing)

---

![Qurani Screenshot](assets/preview.png)

</div>

---

## Download

| Platform | Download | Requirements |
|----------|----------|--------------|
| **Windows** | [Qurani-Setup-2.4.1.exe](https://github.com/qurani-app/qurani/releases/latest) | Windows 10+, 64-bit |
| **Android** | [Qurani-2.4.1.apk](https://github.com/qurani-app/qurani/releases/latest) | Android 8.0+ |

> **Windows:** if Windows SmartScreen appears, click **More info → Run anyway.**
> **Android:** enable **Install from unknown sources** in your device settings before installing the APK.

---

## Features

- **20+ Translations** — switch between English and multilingual translations, compare side-by-side
- **Clean Arabic Typography** — Hafs rendering with adjustable font size, line height, and optional tajweed color coding
- **Bookmarks & Notes** — mark verses, add personal notes, resume exactly where you left off
- **Offline Access** — full Quran available without a connection, download once and read anywhere
- **Reading Progress** — daily reading goals, session history, and a simple streak tracker
- **No Ads. Ever.** — free and completely ad-free, built to serve the reader

---

## Build from Source

### Prerequisites

```bash
node >= 18
npm >= 9
```

### Clone and install

```bash
git clone https://github.com/qurani-app/qurani.git
cd qurani
npm install
```

### Run in dev mode

```bash
npm run dev
```

### Build for Windows

```bash
npm run build:windows
# output: dist/Qurani-Setup-x.x.x.exe
```

### Build for Android

```bash
npm run build:android
# output: dist/Qurani-x.x.x.apk
```

---

## Project Structure
