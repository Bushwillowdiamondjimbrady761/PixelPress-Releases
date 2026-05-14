# Pixel Press Releases

[![Website](https://img.shields.io/badge/website-ghostlyinc.com-0969da?logo=firefoxbrowser&logoColor=white)](https://ghostlyinc.com/en-us/tools/pixel-press/)
[![Windows Store](https://img.shields.io/badge/Windows-Microsoft%20Store-0078d4?logo=microsoftstore&logoColor=white)](https://apps.microsoft.com/detail/9NRMXB13BBN7)
[![Ubuntu .deb](https://img.shields.io/github/v/release/Nix1983/PixelPress-Releases?label=Ubuntu%20%2F%20Debian%20.deb&logo=ubuntu&logoColor=white&color=e95420)](https://github.com/Nix1983/PixelPress-Releases/releases/latest)
[![License](https://img.shields.io/badge/license-proprietary-6f42c1)](#license)

Public downloads for Pixel Press, a local image optimizer from Ghostly Inc.

Pixel Press compresses images on your own machine. Your files stay local:
no upload, no cloud processing, no account required.

## Get Pixel Press

| Platform | Download |
|:--|:--|
| Windows | [Install from Microsoft Store](https://apps.microsoft.com/detail/9NRMXB13BBN7) |
| Ubuntu / Debian Linux | [Download the latest `.deb` package](https://github.com/Nix1983/PixelPress-Releases/releases/latest) |
| Product page | [ghostlyinc.com/en-us/tools/pixel-press](https://ghostlyinc.com/en-us/tools/pixel-press/) |

Windows users should install Pixel Press from the Microsoft Store. Linux builds
are published here as public release artifacts.

## What It Does

- Batch-compress local images without sending them anywhere.
- Add individual files or whole folders.
- Convert supported source images to modern web-friendly formats.
- Choose WebP and/or AVIF output.
- Keep unsupported or broken files out of the conversion instead of crashing.
- Save optimized files into a separate output folder.

## Supported Formats

| Direction | Formats |
|:--|:--|
| Input | JPEG, JPG, PNG, WebP, AVIF |
| Output | WebP, AVIF |

Available formats can depend on the bundled ImageMagick runtime used by the
build. The app only enables output formats that are supported by the current
runtime.

## Ubuntu / Debian Installation

Download `PixelPress-linux-x64.deb` from the
[latest release](https://github.com/Nix1983/PixelPress-Releases/releases/latest),
then install it with:

```bash
cd ~/Downloads
sudo apt install ./PixelPress-linux-x64.deb
```

Start Pixel Press from your application launcher, or run:

```bash
pixelpress
```

## Update

Download the newest `.deb` package from the latest release and install it over
the existing version:

```bash
cd ~/Downloads
sudo apt install ./PixelPress-linux-x64.deb
```

## Uninstall

```bash
sudo apt remove pixelpress
```

## About This Repository

This repository intentionally contains only public release notes and downloadable
Linux release artifacts. The application source code lives in a private
repository.

## License

Pixel Press is proprietary software by Ghostly Inc. This release repository is
not an open-source source-code repository, and no open-source license is granted
for the application source or binaries unless a separate license agreement says
otherwise.
