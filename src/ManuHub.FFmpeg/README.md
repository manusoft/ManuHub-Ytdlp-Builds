![Static Badge](https://img.shields.io/badge/ManuHub.FFmpeg-blue) ![NuGet Version](https://img.shields.io/nuget/v/ManuHub.FFmpeg)  ![NuGet Downloads](https://img.shields.io/nuget/dt/ManuHub.FFmpeg)

# ManuHub.FFmpeg

**ManuHub.FFmpeg** provides a **prebuilt FFmpeg executable** bundled specifically for use with **yt-dlp**.

This package is designed to complement the **Ytdlp.NET** library and **YTDLP-Wrapper** library or developers who want zero-setup media processing when using **yt-dlp** in .NET applications. The **FFmpeg** binary is included in the NuGet package and placed in the tools directory for easy access at build or runtime.

## ✨ Features  
- Precompiled **FFmpeg executable** 
- Optimized for **yt-dlp post-processing**  
- No system-wide FFmpeg installation required
- Works seamlessly with ```ManuHub.Ytdlp```
- Ideal for CI/CD, desktop apps, and self-contained deployments

## 📦 Package Contents

```bash
Tools/
 └─ ffmpeg.exe
```

## 🚀 Usage

```bash
--ffmpeg-location <path-to-tools-folder>
```

In .NET projects, you can reference the ```tools``` directory at runtime or copy the executable to your output folder as part of your build process.

## 🔗 Related Packages
- **ManuHub.Ytdlp** – Latest stable yt-dlp executable
- **ManuHub.FFprobe** – Latest FFprobe for media inspection

## ⚠ Disclaimer
This package does not modify **FFmpeg** in any way.
**FFmpeg** is distributed as a **third-party binary** under its own license.

