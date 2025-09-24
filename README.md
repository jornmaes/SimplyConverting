# SimplyConverting
A fast, simple, offline and modern file conversion tool built with PySide6.  

Easily convert images, audio, video, and even extract archives — all in one clean interface.

---

## Features
- **Batch conversion** — drag and drop multiple files at once
- **Image formats**: JPEG, PNG, WebP, AVIF, ICO, HEIC
- **Audio formats**: MP3, WAV, FLAC, OGG
- **Video formats**: MP4, AVI, MKV, MOV, WEBM, FLV, 3GP
- **Archives**: ZIP, RAR, 7z — extracts compressed contents
- **Custom settings** per format:
  - Image quality, icon size
  - Audio bitrate & sample rate
  - Video resolution, bitrate & FPS
- **Smart handling**:
  - Duplicate file detection
  - Safe overwrite options (rename, overwrite, skip, cancel)
  - Cancel ongoing conversions (with cleanup)
- **Polished UI** with splash screen, styled widgets, and drag-and-drop
- **Login system** with Firebase (persistent sessions, premium support)

---

## Download
Get the latest version from the **[Releases page](https://github.com/jornmaes/SimplyConverting/releases)**.  

- Windows installer (`.exe`) 

> On first launch, Windows may warn about an “Unknown Publisher.”  
> This is normal since the app is not code-signed. Click **More Info → Run Anyway**.

---

## Screenshots


---

## Tech Stack
- **UI**: PySide6 (Qt for Python)
- **Conversion engine**: FFmpeg, Pillow, MoviePy, Pydub
- **Auth & storage**: Firebase
- **Installer**: PyInstaller + NSIS

---

## License & Attribution
- My code is licensed under a **proprietary license** (see [LICENSE.txt](LICENSE.txt))
- Third-party licenses are provided in [`ATTRIBUTIONS.txt`](ATTRIBUTIONS.txt) and the [`licenses/`](licenses/) folder

---

## Feedback
Issues and feature requests are welcome in the [Issues](https://github.com/jornmaes/SimplyConverting/issues) tab.  
