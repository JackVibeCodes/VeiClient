# VeiClient

<p align="center">
  <img src="src/main/resources/assets/veiclient/textures/icon.png" width="96" height="96" alt="VeiClient logo">
</p>

<p align="center">
  <b>A premium, modern Minecraft 1.21.4 Fabric client.</b><br>
  Blue → Purple gradient aesthetic. Sleek ClickGUI. Draggable HUD. Modular architecture.
</p>

---

## ✨ Features

- **ClickGUI** — Category sidebar, live search, animated module cards, smooth open/close transitions, gradient highlights.
- **HUD System** — Draggable elements: Watermark, FPS, CPS, Coordinates, Ping, Active Modules list.
- **Module Framework** — Combat, Movement, Render, Player, Misc, and Client categories with per-module settings, keybinds, and toggle animations.
- **Theme Manager** — Centralised blue→purple (`#3B82F6` → `#A855F7`) colour system used across every UI surface.
- **Event Bus** — Lightweight annotation-driven (`@EventListener`) pub/sub system.
- **JSON Config** — Module states, settings, keybinds, and HUD positions persist automatically to `config/veiclient/`.
- **Chat Commands** — `.help`, `.toggle`, `.bind`, `.config save|load`.

## 📦 Included Modules

| Category | Modules |
|---|---|
| Combat   | KillAura, Reach |
| Movement | Sprint, Fly, Speed |
| Render   | ESP, Fullbright, Tracers |
| Player   | NoFall, AutoEat |
| Misc     | ChatSpam |
| Client   | ClickGUI opener, HUD Editor |

## ⌨️ Default Keybinds

| Key | Action |
|---|---|
| `Right Shift` | Open ClickGUI |
| `Home` | Open HUD Editor |
| `R` | Toggle KillAura |
| `F` | Toggle Fly |
