# Pixel Press Releases

[![Website](https://img.shields.io/badge/website-ghostlyinc.com-0969da?logo=firefoxbrowser&logoColor=white)](https://ghostlyinc.com/en-us/tools/pixel-press/)
[![Windows Store](https://img.shields.io/badge/Windows-Microsoft%20Store-0078d4?logo=microsoftstore&logoColor=white)](https://apps.microsoft.com/detail/9NRMXB13BBN7)
[![Ubuntu .deb](https://img.shields.io/github/v/release/Nix1983/PixelPress-Releases?label=Ubuntu%20.deb&logo=ubuntu&logoColor=white&color=e95420)](https://github.com/Nix1983/PixelPress-Releases/releases/latest)
[![Linux downloads](https://img.shields.io/github/downloads/Nix1983/PixelPress-Releases/total?label=Linux%20downloads&logo=linux&logoColor=white&color=2ea44f)](https://github.com/Nix1983/PixelPress-Releases/releases)

## About

Pixel Press is a local image optimizer from Ghostly Inc. It makes images smaller
on your own machine, so your pictures stay local: no upload, no cloud
processing, no account required.

Learn more on the
[Pixel Press website](https://ghostlyinc.com/en-us/tools/pixel-press/).

## Downloads

| Platform | Recommended download |
|:--|:--|
| Windows | [Install from Microsoft Store](https://apps.microsoft.com/detail/9NRMXB13BBN7) |
| Ubuntu / Debian Linux | [Download the latest `.deb` package](https://github.com/Nix1983/PixelPress-Releases/releases/latest) |
| Website | [Pixel Press product page](https://ghostlyinc.com/en-us/tools/pixel-press/) |

This repository intentionally contains only public release notes and downloadable
Linux release artifacts. The Windows version is distributed through the
Microsoft Store.

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
sudo apt install ./PixelPress-linux-x64.deb
```

## Uninstall

```bash
sudo apt remove pixelpress
```

## Notes

- Linux packages are currently published as `amd64` `.deb` builds.
- Windows users should use the Microsoft Store version.
- The application source is not published in this release repository.
