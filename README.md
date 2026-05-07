# ScreenForge — Force PC Games Into Borderless Windowed Mode

**ScreenForge** automatically forces PC games into borderless windowed mode — no manual config editing, no command line needed.

**[Download on Gumroad](https://alphakiir.gumroad.com/l/screenforge)** | **[Website](https://alphakiir.github.io/screenforge)**

---

## What problem does it solve?

Exclusive fullscreen mode causes:
- Alt-tab freezes or crashes the game
- Discord overlay not showing
- OBS/streaming software can't capture properly
- Game minimizes randomly
- Can't move mouse to second monitor

ScreenForge eliminates exclusive fullscreen in **one click**.

---

## How it works

ScreenForge detects your game, automatically finds and edits its config file, then applies borderless windowed mode. It also prevents the game from reverting to fullscreen on next launch.

Includes a **Shift+F1 in-game overlay** with real-time FPS stats — works on top of any game like Discord's overlay.

---

## Supported Games

| Game | Notes |
|------|-------|
| **Metro Exodus** | Auto-edits user.cfg (r_fullscreen) |
| **Metro Exodus Enhanced Edition** | Auto-edits user.cfg |
| **Metro 2033 Redux** | Auto-edits user.cfg |
| **Metro Last Light Redux** | Auto-edits user.cfg |
| **Resident Evil 2 Remake** | Auto-edits config |
| **Resident Evil 3 Remake** | Auto-edits config |
| **Resident Evil 4 Remake** | Auto-edits config |
| **LEGO Star Wars: The Complete Saga** | DX9 proxy method |
| **LEGO Marvel Super Heroes** | DX9 proxy method |
| **LEGO Marvel Super Heroes 2** | DX9 proxy method |
| **LEGO Indiana Jones** | DX9 proxy method |
| **LEGO The Lord of the Rings** | DX9 proxy method |
| **S.T.A.L.K.E.R. 2: Heart of Chornobyl** | Auto-edits config |
| **Elden Ring** | Auto-edits config |
| **Final Fantasy XIV** | Auto-edits config |
| **Honkai: Star Rail** | Auto-edits config |

More games added with each update.

---

## Features

- One-click borderless windowed mode for 18+ games
- Automatically edits game config files — no manual work
- Prevents games from reverting to fullscreen
- **Shift+F1 overlay** with FPS, resolution and game options
- Multi-monitor support — cursor moves freely between screens
- Works alongside Discord, OBS, streaming software
- Compatible with anti-cheat games
- Windows 10 / 11

---

## Download

**[alphakiir.gumroad.com/l/screenforge](https://alphakiir.gumroad.com/l/screenforge)**

---

## FAQ

**Metro Exodus doesn't have a borderless option — how does ScreenForge fix it?**
ScreenForge edits the user.cfg file directly, changing _fullscreen on to _fullscreen off, then applies the borderless window style automatically.

**LEGO Star Wars TCS reverts to fullscreen — how is this fixed?**
Old LEGO games use DirectX 9 and don't respect config changes at launch. ScreenForge uses a DX9 proxy method that intercepts the fullscreen call and overrides it with borderless windowed.

**Does it work with anti-cheat (EAC, BattlEye)?**
Yes — ScreenForge only modifies config files and window styles. It does not inject into game processes.