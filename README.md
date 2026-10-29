# file.nait

A fast file archiver for Windows: a lighter replacement for 7-Zip and WinRAR.

**Download:** [latest release](https://github.com/aywalh/file.nait/releases/latest) or https://file-nait.vercel.app

## What it does

- **Packs into `.nait`**: its own format, packed on every CPU core at once. Photos, videos and other already-compressed files are stored as-is instead of wasting time on them.
- **Opens and unpacks** `.nait`, `.zip`, `.7z`, `.rar`, `.tar`, `.tar.gz` / `.tgz`, including password-protected zip and 7z.
- **Right-click menu in Explorer**: Extract here, Extract to folder, Add to *name*.nait.
- **Compression levels**: Store, Fastest, Fast, Normal (default), Maximum, Ultra.
- **Progress window**: speed, time left, files, sizes. Pause, Cancel and Background buttons.
- **Zip bomb protection**: archives that would unpack to over 1000× their own size are refused, and free disk space is checked before unpacking.
- **Updates itself**: when a new release is out, an *Update* button appears in the app.

## Install

1. Download `nait-win64.exe` from the [latest release](https://github.com/aywalh/file.nait/releases/latest).
2. Open it. That's the whole app; there's nothing to unzip.
3. For the right-click menu, click **Add to right-click menu** in the app. Windows asks for admin once.

Windows 10/11, 64-bit.

## Privacy

file.nait works offline. The only network request it makes is the update check: when the main window opens, it asks GitHub which release is newest. No accounts, no telemetry, nothing about your files ever leaves your PC.

## License

file.nait is free to use, but it is not open source. All rights reserved. Please don't redistribute modified copies.
