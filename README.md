# The After-Hours

A first-person co-op horror game set in the Backrooms, built with Godot 4.7.
Walk the yellow halls with a failing torch, listen for what's walking with you, and don't look away from
the things that only move when nobody is watching.

The After-Hours is an unofficial, modified version of
[godot-backrooms](https://github.com/MehdiBen2/godot-backrooms) by MehdiBen2. See [Credits](#credits).

## Download and play (Windows)

1. Open the [latest release](https://github.com/OrangeDaCat/the-after-hours/releases/latest) and download
   `The-After-Hours-windows.zip`.
2. Extract the **whole** zip into a folder. Keep `backrooms.exe` and `backrooms.pck` together.
3. Run `backrooms.exe`.

Windows may show a SmartScreen warning because the game isn't code-signed. Click **More info**, then
**Run anyway**.

## Controls

| Key | Action |
| --- | --- |
| WASD / arrows | Move |
| Shift | Sprint (uses stamina) |
| C / Ctrl | Crouch |
| Space | Jump |
| F | Torch on/off |
| Q (hold) | T.S.R.A. field scanner: hold on an entity near the crosshair to log it |
| G / right click | Camera flash (2 per run): blinds the Bacteria for a few seconds if it catches it full in the face |
| X (hold) + mouse wheel | Camcorder zoom, up to 4x |
| T (hold) | Reflective hazard tape: stick it on walls and floors to mark corridors you've walked. Hold on a strip to peel it off |
| Tab | Inventory (T.S.R.A. field terminal) |
| V | Push-to-talk (when voice is set to push-to-talk) |
| Esc | Pause / settings |
| F11 or Alt+Enter | Fullscreen |

Keys can be rebound under Settings > Keybinds.

## Co-op

Up to 8 players. Internet is needed on both sides.

- **Host:** press HOST GAME in the menu. After a few seconds a short room code appears (for example `K7Q-M2X`).
  Share it with your friends.
- **Join:** type the room code into JOIN.
- Everyone must run the same release. Mismatched builds are refused with a *VERSION MISMATCH* message.

## Credits

The original game, design, code and content belong to its author, MehdiBen2:
<https://github.com/MehdiBen2/godot-backrooms>. This project is not affiliated with or endorsed by them.
Changes in this version are by OrangeDaCat.

Built with [Godot Engine](https://godotengine.org) (MIT licence). Full credits for the third-party audio,
models and textures used by the game are in [CREDITS.txt](CREDITS.txt).
