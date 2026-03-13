![Static Badge](https://img.shields.io/badge/ManuHub.Deno-orange) ![NuGet Version](https://img.shields.io/nuget/v/ManuHub.Deno)  ![NuGet Downloads](https://img.shields.io/nuget/dt/ManuHub.Deno)

# ManuHub.Deno

**ManuHub.Deno** provides the official **deno.exe** binary from **denoland/deno**, required as an external JavaScript runtime for **yt-dlp** since late 2025.

This package is designed to work seamlessly with **ManuHub.Ytdlp**, **ManuHub.FFmpeg**, **ManuHub.FFprobe**, and libraries such as **Ytdlp.NET** or **YTDLP-Wrapper** — enabling full YouTube support with **zero manual Deno installation**.

## ✨ Features  

- Official stable **deno.exe** from denoland/deno
- No global Deno installation required
- Required for yt-dlp ≥ 2025.11.12 to handle YouTube JS challenges & signature extraction
- Works perfectly with yt-dlp's default runtime priority (Deno first)
- Ideal for self-contained .NET applications, CI/CD pipelines, and desktop tools

## 📦 Package Contents

```bash
Tools/
 └─ deno.exe
```

## 🚀 Usage

yt-dlp will automatically detect deno.exe if it's in the PATH or in a known location.
In .NET projects you can locate it like this:

```bash
--js-runtimes deno:<path-to-tools-folder>
```

In .NET projects, you can reference the ```tools``` directory at runtime or copy the executable to your output folder as part of your build process.
Most modern yt-dlp wrappers already handle runtime discovery automatically when the binary is in the output directory or PATH.

## 🔗 Related Packages

- **ManuHub.Ytdlp** – Latest stable yt-dlp executable
- **ManuHub.FFmpeg** – Latest FFmpeg for post-processing
- **ManuHub.FFprobe** – Latest FFprobe for media inspection

## ⚠ Disclaimer

This package **does not modify Deno** in any way.

**Deno** is distributed as a **third-party binary** under its own license.

[Project website](https://deno.com/)

