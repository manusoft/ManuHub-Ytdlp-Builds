![Static Badge](https://img.shields.io/badge/ytdlp_executable-red) ![NuGet Version](https://img.shields.io/nuget/v/YTDLP-Executable)  ![NuGet Downloads](https://img.shields.io/nuget/dt/YTDLP-Executable)

# Ytdlp-Executable (Legacy)

> ⚠️ This package is now **legacy** and will no longer receive updates.

**Ytdlp-Executable** was a NuGet package that provided the `yt-dlp.exe` binary for .NET applications.

This package is being replaced by the new **ManuHub.Ytdlp** package set, which provides a more structured and actively maintained ecosystem for yt-dlp integration.

---

## Migration

Please migrate to the new packages:

- **ManuHub.Ytdlp**
- **ManuHub.Deno**
- **ManuHub.FFmpeg**
- **ManuHub.FFprobe**

These packages provide:

- Improved runtime integration
- Better version management
- Future updates and support

## Legacy Behavior (for existing users)

Previously, this package:

- Included the `yt-dlp.exe` binary
- Copied the file to the output directory:

  ```Tools/yt-dlp.exe```

- Was commonly used together with wrapper libraries such as:
  - Ytdlp.NET
  - Other custom process-based integrations

---

## Supported Sites

yt-dlp supports thousands of websites.  
See the official project documentation for the full list.

---

## Status

- Maintenance: ❌ Stopped  
- Security updates: ❌ Not guaranteed  
- Replacement: ✅ ManuHub.Ytdlp

---

## Author

**ManuHub**