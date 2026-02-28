![Static Badge](https://img.shields.io/badge/ManuHub.Ytdlp-red) ![NuGet Version](https://img.shields.io/nuget/v/ManuHub.Ytdlp)  ![NuGet Downloads](https://img.shields.io/nuget/dt/ManuHub.Ytdlp)

# ManuHub.Ytdlp 

**ManuHub.Ytdlp** provides the **latest stable yt-dlp executable** bundled as a NuGet package for use in **.NET applications**.

This package is intended for developers who want to use **yt-dlp without requiring a system-wide installation**, making it ideal for desktop apps, CI/CD pipelines, and self-contained deployments.

The yt-dlp binary is included in the package and placed in the ```Tools``` directory.

## ✨ Features  
- Latest stable **yt-dlp executable**
- No external yt-dlp installation required
- Simple integration with .NET projects
- Works seamlessly with FFmpeg / FFprobe companion packages
- Suitable for Windows desktop, automation, and build pipelines

## 📦 Package Contents

```bash
Tools/
 └─ yt-dlp.exe
```

## 🚀 Usage
yt-dlp can be executed directly from the tools directory or copied to your application’s output folder at build time.

Example command-line usage:

```bash
yt-dlp https://www.youtube.com/watch?v=VIDEO_ID
```

When using FFmpeg for post-processing, pair this package with:
- **ManuHub.FFmpeg** – Latest FFmpeg for post-processing
- **ManuHub.FFprobe** – Latest FFprobe for media inspection

## ⚠ Disclaimer

This package redistributes the official, unmodified yt-dlp executable.
- yt-dlp is a **third-party project**
- This package is **not affiliated with or endorsed by the yt-dlp project**
- No modifications are made to the original binary

## 📜 License & Attribution

### This package
The packaging logic and metadata are licensed under the **MIT License**.

### yt-dlp
yt-dlp is licensed under the Unlicense.

[Project website](https://github.com/yt-dlp/yt-dlp/)

## 🧠 Versioning
The NuGet package version follows the yt-dlp release version.

Packaging-only updates may use an additional revision number when required.

Example:- yt-dlp.exe v2026.2.21 - ManuHub.Ytdlp v6.2.21

## ⭐ Why this package?

Because sometimes you just want:
- dotnet restore
- run yt-dlp
- done 😄

No installers. No PATH issues. No surprises.

##  Supported Sites
- [Thousands of sites](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md)