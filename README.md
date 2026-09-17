<img align="left" src="https://cdn.modrinth.com/data/ZDCwiIc3/c6a7ece0167f8f4f4703a9468b125321a47d34bd.png" width="160" alt="Renice Shot logo">

<p><strong><font size="6">Renice Shot</font></strong></p>

A lightweight client-side Fabric mod for taking high-resolution screenshots.

It keeps the familiar [Fabrishot](https://github.com/ramidzkh/fabrishot) workflow while focusing on faster support for new mc versions and more reliable screenshot capture.

<br clear="left"/>

---

## Download

[![MODRINTH](https://img.shields.io/badge/MODRINTH-00AF5C?style=for-the-badge&logo=modrinth&logoColor=white&labelColor=000000)](https://modrinth.com/mod/renice-shot)
[![CURSEFORGE](https://img.shields.io/badge/CURSEFORGE-F16436?style=for-the-badge&logo=curseforge&logoColor=white&labelColor=000000)](https://www.curseforge.com/minecraft/mc-mods/renice-shot)

---

## Screenshot controls

Press **F9** to take a screenshot.

The game is temporarily rendered at the configured resolution, the screenshot is captured, and the original resolution is restored automatically.

By default, screenshots are captured at **3840 × 2160 (4K)**.

## Features

- Custom screenshot width and height
- PNG, JPG, TGA and BMP output
- Optional HUD hiding during capture
- Configurable capture delay
- Custom screenshot file names with `%time%` and `%world%` variables
- Automatic restoration of resolution and HUD state
- Cleanup of incomplete screenshot files and in-game error reporting

Screenshots are saved to Minecraft's default `screenshots` folder with the `huge_` prefix by default.

## Configuration

With [Mod Menu](https://github.com/TerraformersMC/ModMenu) and [Cloth Config](https://github.com/shedaniel/cloth-config) installed, Renice Shot can be configured directly in-game. Both are optional.

Without them, settings can be changed manually in: `config/renice-shot.properties`

The maximum screenshot resolution depends on the limits supported by your graphics hardware.
