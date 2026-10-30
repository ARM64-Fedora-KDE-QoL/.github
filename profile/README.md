# ARM64 Fedora KDE Quality-of-Life Improvements

**Built on ARM64 Linux Fedora 44 Asahi KDE Plasma**

Small, polished improvements for **laptops running Fedora KDE Plasma on ARM64**, such as Apple Silicon MacBooks with Fedora Asahi Remix. Made for people who've recently switched to Linux and want their touchpad and desktop to feel smooth, without hand-editing config files. Every improvement installs with one command and keeps itself working after Fedora updates.

## Start here

**[ARM64-Fedora-KDE-QoL](https://github.com/ARM64-Fedora-KDE-QoL/ARM64-Fedora-KDE-QoL)** installs everything below at once:

```bash
git clone https://github.com/ARM64-Fedora-KDE-QoL/ARM64-Fedora-KDE-QoL.git
cd ARM64-Fedora-KDE-QoL
./install.sh
```

## The improvements

| Project | What it does |
|---|---|
| [**3-Finger-Cube-Gesture**](https://github.com/ARM64-Fedora-KDE-QoL/3-Finger-Cube-Gesture) | 3-finger swipe **up** opens KDE's Desktop Cube, swipe **down** closes it, and swiping **left/right** in the open cube turns it smoothly with your fingers. Rebuilds itself after KWin and KDE updates. |
| [**Cube-Backside-Click**](https://github.com/ARM64-Fedora-KDE-QoL/Cube-Backside-Click) | Click the **back** of a desktop inside the open cube to switch to it. No sudo needed. |

Each project can also be installed on its own. All are open source under the GPL-3.0.
