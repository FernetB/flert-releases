# Flert: the builds

Flert is a spell duel for two to four benders, TowerFall style: pick two of fire, earth,
air and water, aim with the mouse, weave your own combos. Play at one PC, against bots, or
online with friends. It also carries a first taste of the next game, THE WOODS (3D): a
forest from above, fog of war, one element each, against bots or friends online.

This repository holds the **ready-to-play builds** (the game's source lives elsewhere).
Every version is a release on the right, or here:
**https://github.com/FernetB/flert-releases/releases/latest**

## Download and play

Nothing to install: unzip and run (unzip it first: a game run from inside the zip cannot
update itself).

| | Get | Run |
|---|---|---|
| **Windows** | `flert-windows.zip` | Double-click `flert.exe`. SmartScreen may say "Windows protected your PC": *More info* > *Run anyway*. |
| **Linux** | `flert-linux.zip` | `./flert.x86_64` (`chmod +x flert.x86_64` first if it will not start). |
| **Mac** | `flert-mac.zip` | Double-click `Flert.app` (Intel and Apple Silicon; macOS 11 or newer, 13 on Apple Silicon). The game is not from the App Store, so the first time macOS says "Apple could not verify Flert": press *Done*, open *System Settings > Privacy & Security*, scroll down to "Flert was blocked" and press *Open Anyway*. (Before macOS 15: right-click `Flert.app` > *Open* > *Open*.) **Drag `Flert.app` into Applications first**: opened from Downloads, macOS will not let it update itself (its updates then go into the Applications folder in your home, `~/Applications`, and you open that one from then on). |

F11 or Alt+Enter (Option+Return on a Mac) toggles fullscreen. Escape leaves a fight for
the menu.

## Updates

The game checks this page when it starts. When a newer version is out, **UPDATE TO x.y.z**
appears on its menu: pick it and the game downloads the new version, puts it in place of
itself and restarts. The version you have is written in the bottom left corner of the menu.
If the game cannot replace itself (a folder it may not write to, or it runs from inside its
zip), the line under the row says why and the row opens this page instead: unzip the new
one by hand.

**On version 0.1.6 or older, on a Mac or on Linux?** Those versions could not always update
themselves: download the latest zip from this page by hand once. From 0.1.7 on, the game
updates itself (on a Mac, keep `Flert.app` in Applications).

## Playing together

Up to four, each on your own PC. One of you picks **PLAY ONLINE > HOST A ROOM** (or **THE
WOODS (3D) > HOST A ROOM** for the forest) and sends the room code; the others pick **JOIN WITH A CODE** and paste it, say READY with jump, and
the host starts. Everyone needs the **same version** (the update row makes that easy).
Windows asks to let the game through the firewall the first time you host, and a Mac
whether Flert may accept connections on your network: say yes.
