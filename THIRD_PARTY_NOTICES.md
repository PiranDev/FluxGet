# Third-party media tools (not bundled)

FluxGet ships without yt-dlp, FFmpeg, or Deno binaries. Media functionality is optional. Users choose whether to install or update these tools using the in-app Media Tools Manager. All executables are supplied by the respective third-party release sources, not the FluxGet repository.

| Tool | Project | License notes | Release source |
| --- | --- | --- | --- |
| yt-dlp | https://github.com/yt-dlp/yt-dlp | Project source: Unlicense; PyInstaller Windows executable includes GPLv3+ code. Consult upstream THIRD_PARTY_LICENSES.txt. | https://github.com/yt-dlp/yt-dlp/releases |
| FFmpeg | https://ffmpeg.org | Build-dependent LGPL 2.1+ / GPL. FluxGet currently selects a build labelled LGPL; independently verify the exact downloaded binary and build configuration. | https://github.com/BtbN/FFmpeg-Builds/releases |
| Deno | https://github.com/denoland/deno | MIT; retain original copyright and license if redistributing. | https://github.com/denoland/deno/releases |

**Important:** This notice does not substitute for the actual licenses and source-correspondence requirements of binaries. Check the licenses, build provenance and checksums of the specific release used. The built-in downloader compares SHA-256 with hashes fetched from release channels; that is not equivalent to independent cryptographic signature verification. Downloading tools through the application does not eliminate potential license or legal responsibilities.

FluxGet is intended for content that users have a right to download. Tool support does not imply endorsement by the platforms supported by those tools and cannot grant permission to download copyrighted material.
