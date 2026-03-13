![Static Badge](https://img.shields.io/badge/ManuHub.FFplay-purple) ![NuGet Version](https://img.shields.io/nuget/v/ManuHub.FFplay)  ![NuGet Downloads](https://img.shields.io/nuget/dt/ManuHub.FFplay)

# ManuHub.FFplay

**ManuHub.FFplay** provides the **FFplay executable** from the FFmpeg project for use in .NET applications.

**FFplay** is a lightweight media player built on top of **FFmpeg** libraries and is commonly used for **testing, previewing, and debugging audio/video streams**.

This package is designed to complement **ManuHub.FFmpeg** and **ManuHub.FFprobe**, enabling **zero-setup media tooling** in .NET applications.

The **FFplay** binary is bundled directly in the NuGet package and placed in the **tools** directory for easy access during build or runtime.

## ✨ Features  

- Precompiled **FFplay executable** 
- No system-wide **FFplay** installation required
- Ideal for **CI/CD, desktop apps**, and **self-contained deployments**
- Works seamlessly with **FFmpeg** and **FFprobe** tools

## 📦 Package Contents

```bash
Tools/
 └─ ffplay.exe
```

## 🚀 Usage

In .NET projects, you can reference the ```tools``` directory at runtime or copy the executable to your output folder as part of your build process.

Example path resolution:

```csharp
var ffplayPath = Path.Combine(AppContext.BaseDirectory, "tools", "ffplay.exe");
```

## 🔗 Related Packages

- **ManuHub.FFmpeg** – Latest FFmpeg binary for media processing
- **ManuHub.FFprobe** – Latest FFprobe binary for media metadata analysis

## ⚠ Disclaimer

This package **does not modify FFplay** in any way.

**FFplay** is part of the **FFmpeg project** and is distributed as a **third-party binary** under the terms of its respective license.

All rights and licenses belong to the **FFmpeg project** and its contributors.

[Project website](https://ffmpeg.org/)

