<div align="center">

<img src=".github/banner.png" alt="Mainframe — A wall of remote desktops" width="100%">

# Mainframe

### A wall of remote desktops

<a href="https://github.com/KVRNL/mainframe/releases/latest"><img alt="Latest version" src="https://img.shields.io/github/v/release/KVRNL/mainframe?display_name=tag&label=version&color=F5A623&labelColor=0d0d0f&style=for-the-badge"></a>
<img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0d0d0f?style=for-the-badge&labelColor=0d0d0f">
<img alt="Price" src="https://img.shields.io/badge/price-FREE-F5A623?style=for-the-badge&labelColor=0d0d0f">
<a href="./LICENSE"><img alt="License" src="https://img.shields.io/badge/license-Proprietary%20Freeware-0d0d0f?style=for-the-badge&labelColor=0d0d0f"></a>

<br>

See up to 36 live remote-desktop connections at once in a clean grid — a security-camera wall for your PCs, servers, and VPSes. Every viewport is live but view-only; click one to take full control.

### **[⬇&nbsp; Download Mainframe — free at kvrnl.io](https://kvrnl.io/products/mainframe/)**

</div>

<br>

---

## What it does

Mainframe turns a pile of remote machines into a single wall you can watch at a glance. Add your PCs, servers, and VPSes and they appear as live RDP viewports in a grid you can size from 2×2 all the way to 6×6. The wall is view-only so nothing gets touched by accident; expand any tile for full control, go true-fullscreen, or yank a single screen out into its own free-floating desktop window and place it wherever you like.

A This-PC panel shows your own machine's address, name, and username so you always know exactly what to connect to, and a toast pops the moment any connection drops. Connections are saved with passwords encrypted by Windows and reconnect on launch. It runs from the system tray and updates itself silently. Free to use — claim your license key and download it straight from this page.

## Features

- **Live RDP wall, 2×2 up to 6×6, view-only by default**
- **Expand for full control, true-fullscreen, or pop out to a floating window**
- **This-PC panel + drop alerts so you're never guessing**
- **Saved connections (encrypted), tray, silent auto-updates**

## Download &amp; install

Mainframe is **completely free**. Each install needs its own license key, which you get
with a free KVRNL account.

1. Go to **[kvrnl.io/products/mainframe/](https://kvrnl.io/products/mainframe/)**
2. Create a free account — email verification, nothing else
3. Claim your license key — instant, no waiting
4. Download and install

> [!NOTE]
> Mainframe isn't code-signed yet, so Windows SmartScreen may warn you on first run.
> Click **More info → Run anyway**. Code signing is on the roadmap.

## Your license key

- **Free, one per product**, issued from your KVRNL account.
- **A key activates on one machine.** The first device to activate it claims it.
- **Switching computers?** Hit **Release device** on your
  [account page](https://kvrnl.io/account/) and the key is free to use again.
- Keys are checked over HTTPS at launch. See [Privacy](#privacy).

## Requirements

- **Windows 10 or 11** (64-bit)
- A free [KVRNL account](https://kvrnl.io/signup/) for your license key

## Privacy

Mainframe sends KVRNL only what's needed to validate your license: **the key, the
product name, and a hardware ID**. No telemetry, no analytics, no tracking, and
none of your files. Full policy: **[kvrnl.io/privacy](https://kvrnl.io/privacy/)**

## What's new

**v1.1.18** — 2026-09-16
  - Fixed the Remote Desktop repair failing after a Windows update on PCs where a security product holds files open. The repair found the right settings for the new Windows build and verified them, but the final step - writing them into place - was refused by Windows and the failure was swallowed, so the old settings stayed live and Remote Desktop stayed down while every check said the data was correct. The write now falls back to the method that has always worked on these machines, retries through a short lock, and if it still can't land it says so plainly instead of reporting the wrong reason.

**v1.1.17** — 2026-09-16
  - The Remote Desktop and Report a problem pages in Settings now fit the window without scrolling. Remote Desktop folds the password and port lines into the note under the sign-in details (and if this PC uses a non-standard port, it now shows up on the address itself, the way it has to be typed). Report a problem puts severity and email side by side. The Screens list, which grows with the PCs you add, is the only page that can still need to scroll.

**v1.1.16** — 2026-09-16
  - The Screen Share page has been redesigned to match the rest of the app: two clear cards - Share this PC and View another PC - with your share code shown large, Copy and New buttons right next to it, a live status (off / waiting / someone connected), and hover hints on everything. While watching someone's screen, the top bar now uses the app's own rounded buttons, monitor switches only appear when they have more than one, and Enter in the code box connects.
  - Fixed the viewer sitting on Reconnecting... over a black screen forever after a wrong share code or a refused connection. It now says plainly that the other PC refused it and why, so you can fix the code and try again. Typing an address with a port (like 192.168.1.5:47921) is honoured too.

**v1.1.15** — 2026-09-16
  - No more stock Windows scrollbar in Settings. When a page is taller than the window it now scrolls behind a slim dark bar that matches the app - mouse wheel anywhere on the page, drag the bar, or click above or below it to move a page at a time. The saved-connections picker in the Add / Edit screen dialog is now the dark dropdown as well, the last stock white list that was reachable from Settings.

**v1.1.14** — 2026-09-16
  - The Settings cog is now on the very first screen, the moment the app launches. You no longer have to pick The Wall or Screen Share just to reach your screens list, the Remote Desktop repair, or the update check. Opening a screen, reconnecting one, or editing one from Settings on that first screen takes you straight to the wall.

Full history → **[kvrnl.io/changelog/mainframe](https://kvrnl.io/changelog/mainframe/)**

## Documentation

Setup guides and how-tos → **[kvrnl.io/docs/mainframe](https://kvrnl.io/docs/mainframe/)**

## Support

> [!IMPORTANT]
> **We don't use GitHub Issues.** Report bugs from inside the app — it's the
> fastest route to us and it attaches the details we need automatically.

- 🐛 **Found a bug?** Use **Report a Problem** inside Mainframe
- 💬 **Chat with us** → **[Discord](https://discord.gg/Ub4SdAuhu)**
- ✉️ **Anything else** → **[kvrnl.io/contact](https://kvrnl.io/contact/)**
- ❓ **FAQ** → [kvrnl.io/faq](https://kvrnl.io/faq/)

## License

**Proprietary freeware — free to use, not open source.**

This repository hosts the installer releases, documentation, and license for
Mainframe. **The application source code is not published.** See
**[LICENSE](./LICENSE)** for the full terms.

---

<div align="center">
<br>

**[kvrnl.io](https://kvrnl.io)** &nbsp;·&nbsp; **[All products](https://kvrnl.io/products/)** &nbsp;·&nbsp; **[Changelog](https://kvrnl.io/changelog/)** &nbsp;·&nbsp; **[Discord](https://discord.gg/Ub4SdAuhu)** &nbsp;·&nbsp; **[Contact](https://kvrnl.io/contact/)**

<sub>© 2026 <b>KVRNL</b> — an AI-powered software studio shipping free desktop tools.</sub>

</div>
