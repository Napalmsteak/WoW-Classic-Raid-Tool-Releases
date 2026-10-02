# WoW Classic Raid Tool

A Windows desktop app for World of Warcraft Classic raid leaders and planners. Keep your guild,
raid groups, raid schedule, BiS lists and loot log in one place, with a built-in item database
of real tooltips and icons that works offline.

Supports **Classic Era**, **Season of Discovery**, **Forever** (beta), **TBC**, **Wrath**,
**Cataclysm** and **Mists of Pandaria Classic**, in nine languages.

![Dashboard](screenshots/dashboard.png)

## Features

- **Guilds:** import your guild roster from Blizzard and see every member's class, level and
  Gear Score. Open a character sheet with their equipped gear, enchants and stats.
- **Roster Builder:** drag players into raid groups for 10, 20, 25 or 40-player raids. Keep a
  bench and notes, and link the roster to the raids it runs.
- **Schedule:** one-off or weekly raid nights. The Dashboard shows what's next.
- **BiS Lists:** import your guild's lists from That's My BiS and track everyone's progress
  against what they actually have equipped.
- **Loot Tracker:** log who got what from which boss, with a +1 system. Boss and item pickers come
  from the raids the roster runs.
- **Item Database:** 68,000+ items with full tooltips and icons, searchable by name, raid, boss or
  source: dungeons, raids, crafting, vendors, reputation, PvP and more. It includes leveling gear
  at every level and every profession's recipes with the materials they need, plus vendor sell
  prices and filters by quality, slot, type, level and class.
- **Alliance or Horde:** a dark theme in your faction's colors and artwork.
- **Your language:** see [Languages](#languages).

## Screenshots

| | |
|---|---|
| ![Guild members](screenshots/guild.png) | ![Character sheet](screenshots/character-sheet.png) |
| **Guild:** members, classes and Gear Score | **Character sheet:** equipped gear with tooltips |
| ![Roster Builder](screenshots/roster.png) | ![Loot Tracker](screenshots/loot.png) |
| **Roster Builder:** a 25-player raid in groups | **Loot Tracker:** the loot log with +1s |
| ![BiS progress](screenshots/bis.png) | ![BiS list](screenshots/bis-detail.png) |
| **BiS Lists:** the guild's progress | **BiS list:** each item against what's equipped |
| ![Item Database](screenshots/database.png) | ![Horde theme](screenshots/dashboard-horde.png) |
| **Item Database:** filtered to Serpentshrine Cavern | **Horde theme** |
| ![Settings in German](screenshots/settings-german.png) | |
| **In German:** Settings, with the language picker | |

*The screenshots show an example guild with real TBC Classic items.*

## Languages

The app is available in:

| | |
|---|---|
| English | Русский (Russian) |
| Deutsch (German) | Português (Brasil) |
| Français (French) | 한국어 (Korean) |
| Español (Spanish) | 简体中文 (Simplified Chinese) |
| | 繁體中文 (Traditional Chinese) |

It starts in your Windows language when it's one of these, otherwise in English. Change it any
time in **Settings ▸ Language**. Classes, roles, slots, stats, professions and item qualities use
the game's own names in each language, and dates and numbers follow the language you choose.

Item names and tooltips are still in English in every language. The translations other than
English are drafts: if something reads wrong in your language, please [open an issue](../../issues).

## Install

1. Open the [latest release](../../releases/latest).
2. Download `WoW.Classic.Raid.Tool_<version>_x64-setup.exe` and run it. It installs for your
   Windows user only, so no administrator rights are needed.

Windows may show a SmartScreen warning because the installer isn't code-signed. Choose
**More info ▸ Run anyway**.

## Updates

The app checks for new versions when it starts and offers to install them. You can also check in
**Settings ▸ About & Updates**. Your data is kept when you update.

## Item data

The app's item database is also published on its own, for use in other tools:
[WoW-Classic-Item-Caches](https://github.com/Napalmsteak/WoW-Classic-Item-Caches).

---

This repository only holds the release downloads. The app's source code is private.
World of Warcraft and its item data © Blizzard Entertainment. This is an unofficial, fan-made tool.
