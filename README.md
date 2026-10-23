# Qurani

A Quran reader for Windows and Android.

Qurani lets you read the Holy Quran with Arabic text, translations, bookmarks, and offline access.

## Features

- Read the Holy Quran in Arabic
- Multiple translations
- Adjustable Arabic font size
- Bookmarks and reading progress
- Offline reading
- Dark theme
- No advertisements

## Download

Download the latest version from the [GitHub Releases](https://github.com/qurani-app/qurani/releases) page.

| Platform | File | Requirements |
|---|---|---|
| Windows | `Qurani-Setup.exe` | Windows 10 or later (64-bit) |
| Android | `Qurani.apk` | Android 8.0 or later |

### Windows

1. Download the `.exe` installer.
2. Run the installer.
3. Follow the installation instructions.

### Android

1. Download the `.apk` file.
2. Allow installation from the download source if prompted.
3. Install and open Qurani.

## Screenshots

![Qurani Preview](assets/preview.png)

## Building from Source

### Requirements

- Node.js 18 or later
- npm 9 or later
- Git
- Android SDK for Android builds, if required by the project

### Clone the repository

```bash
git clone https://github.com/qurani-app/qurani.git
cd qurani
npm install
```

### Development

```bash
npm run dev
```

### Build for Windows

```bash
npm run build:windows
```

### Build for Android

```bash
npm run build:android
```

Build outputs are generated in the `dist/` directory if configured in the project.

## Project Structure

```text
qurani/
├── assets/
│   ├── logo.png
│   └── preview.png
├── src/
├── package.json
├── package-lock.json
├── LICENSE
└── README.md
```

## Contributing

Contributions are welcome. Open an issue to report bugs or suggest features, or submit a pull request.

## Issues

[GitHub Issues](https://github.com/qurani-app/qurani/issues)

## License

See the [LICENSE](LICENSE) file for details.
