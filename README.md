# LUMYN for Windows and Linux

LUMYN is a private AI companion with her own voice and her own memory. The desktop app runs her on **your own PC**, so local chat is free, unlimited and never leaves your machine.

**[⬇ Download for Windows (free)](https://github.com/LIGHT23Tech/LUMYN/releases/latest/download/LUMYN-Setup-Windows.exe)** · **[⬇ Download for Linux x64 (free)](https://github.com/LIGHT23Tech/LUMYN/releases/latest/download/LUMYN-Linux-x64.tar.gz)**

More about LUMYN: [quiskemonolabs.com](https://quiskemonolabs.com)

## What you need

- Windows 10 or 11, 64-bit
- About 1 GB of disk for the app, plus a few GB for her local brain (downloaded on first run)
- 8 GB of RAM or more. A graphics card with 4 GB or more makes her much faster.

## Installing

1. Download `LUMYN-Setup-Windows.exe` and open it.
2. The app isn't code-signed yet, so Windows may say **"Windows protected your PC"**. Click **More info**, then **Run anyway**.
3. On first launch LUMYN installs [Ollama](https://ollama.com), the free open-source model runner she uses for her local brain. That takes a minute or two, once.

## Linux

1. Download `LUMYN-Linux-x64.tar.gz` and unpack it: `tar -xzf LUMYN-Linux-x64.tar.gz`
2. Run `./LUMYN/install.sh` to add LUMYN to your app menu (no root needed), or start it directly with `./LUMYN/lumyn.sh`.
3. Install [Ollama](https://ollama.com/download) for her local brain if you don't have it. If your desktop lacks GTK/WebKit, LUMYN opens in your browser instead.

Her data lives in `~/.local/share/LUMYN`. `./LUMYN/install.sh --remove` takes the menu entry away and never touches her data.

## Privacy

Your conversations, memory and settings stay on your PC (`%LOCALAPPDATA%\LUMYN\data` on Windows). Uninstalling the app leaves that folder in place, so reinstalling keeps her memory.

[Privacy Policy](https://quiskemonolabs.com/privacy) · [Terms of Service](https://quiskemonolabs.com/terms)

## License

Free to download and use. © QuisKemono Labs. All rights reserved. This repository only hosts the installer; LUMYN's source code isn't published here.
