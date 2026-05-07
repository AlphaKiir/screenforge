# ScreenForge — Force PC Games Into Borderless Windowed Mode

**ScreenForge** automatically forces PC games into borderless windowed mode — no manual config editing, no command line needed.

**[Download on Gumroad](https://alphakiir.gumroad.com/l/screenforge)** | **[Website](https://alphakiir.github.io/screenforge)**

---

## What problem does it solve?

Exclusive fullscreen mode causes:
- Alt-tab freezes or crashes the game
- Discord overlay not showing
- OBS/streaming software cant capture properly
- Game minimizes randomly
- Cant move mouse to second monitor

ScreenForge eliminates exclusive fullscreen in **one click**.

---

## Supported Games

| Game | Notes |
|------|-------|
| **Metro Exodus** | Auto-edits user.cfg |
| **Metro Exodus Enhanced Edition** | Auto-edits user.cfg |
| **Metro 2033 Redux** | Auto-edits user.cfg |
| **Metro Last Light Redux** | Auto-edits user.cfg |
| **Resident Evil 2 Remake** | Auto-edits config |
| **Resident Evil 3 Remake** | Auto-edits config |
| **Resident Evil 4 Remake** | Auto-edits config |
| **LEGO Star Wars: The Complete Saga** | DX9 proxy method |
| **LEGO The Lord of the Rings** | DX9 proxy method |
| **LEGO Indiana Jones** | DX9 proxy method |
| **LEGO Marvel Super Heroes** | DX9 proxy method |
| **CS2 (Counter-Strike 2)** | Auto-edits config |
| **Warframe** | Auto-edits config |

---

## Features

- One-click borderless windowed mode for 13 games
- Automatically edits game config files
- Prevents games from reverting to fullscreen
- **Shift+F1 overlay** with FPS stats
- Multi-monitor cursor support
- Discord and OBS compatible
- Windows 10 / 11

---

## Download

**[alphakiir.gumroad.com/l/screenforge](https://alphakiir.gumroad.com/l/screenforge)**

---

## FAQ

**Metro Exodus has no borderless option — how does ScreenForge fix it?**
ScreenForge edits the `user.cfg` file, changing `r_fullscreen on` to `r_fullscreen off`, then applies the borderless window style.

**LEGO Star Wars TCS reverts to fullscreen — how is this fixed?**
ScreenForge uses a DX9 proxy that intercepts the fullscreen call at startup. The game cannot revert it.

**Does it work with anti-cheat?**
Yes — ScreenForge only modifies config files and window styles. No code injection.
