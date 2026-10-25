# manhuntK 🧭

[![Minecraft Version](https://img.shields.io/badge/Minecraft-Paper%201.21.x-brightgreen.svg)](https://papermc.io)
[![Java Version](https://img.shields.io/badge/Java-21-blue.svg)](https://adoptium.net)
[![Latest Release](https://img.shields.io/github/v/release/krishnamittal0409-commits/manhuntK-Release?color=orange&label=Latest%20Version)](https://github.com/krishnamittal0409-commits/manhuntK-Release/releases/latest)

A modern, high-performance **Manhunt (Speedrunner vs Hunter)** plugin designed from the ground up for **Paper 1.21+** Minecraft servers.

---

## 📥 Official Download

> [!IMPORTANT]
> **Download the Latest Protected JAR:**  
> 👉 **[Download manhuntK.jar (Latest Release)](https://github.com/krishnamittal0409-commits/manhuntK-Release/releases/latest)**

*Note: Older releases are automatically retired upon each new release to ensure all servers run the most up-to-date, secure version.*

---

## ✨ Features

* **Multi-Speedrunner & Multi-Hunter Compatibility:** Play with any number of hunters and runners simultaneously.
* **Modern In-Game Radar Menu:**
  * Right-click your tracking compass to open an interactive chest GUI displaying all alive speedrunners' real player skin heads.
  * Live distance meter and dimension indicators (`Overworld 🌿`, `The Nether 🔥`, `The End 🌌`).
  * 1-click lock needle onto any speedrunner.
* **Teammate-Only Health Visibility:**
  * Hunters can only see fellow Hunters' live health. Enemy speedrunner health is hidden (`???`).
  * Speedrunners can only see fellow Speedrunners' live health.
* **Cross-Dimension Compass Tracking:**
  * Uses modern Paper 1.21 Lodestone tracking coordinates (works across Overworld, Nether, and End).
  * Automatically points to the speedrunner's last portal exit when in different dimensions.
* **Interactive Control Dashboard:**
  * Run `/manhunt menu` or `/mh gui` to manage matches, select teams, or reset with one click.
* **Auto-Refreshing Radar:** Compass needle recalculates automatically every 5 seconds (100 ticks).
* **Automatic Update Alerts:** Server administrators receive in-game pings whenever a new update is released.

---

## 📜 Commands Reference

| Command | Permission | Description |
| :--- | :--- | :--- |
| `/manhunt menu` *(or `/mh gui`)* | `manhunt.admin` | Opens the modern interactive control dashboard |
| `/compass` | `manhunt.compass` | Retrieves or refreshes your tracking radar compass |
| `/manhunt start` | `manhunt.admin` | Starts the match and equips hunters with compasses |
| `/manhunt stop` | `/manhunt.admin` | Halts tracking and pauses the game |
| `/manhunt reset` | `manhunt.admin` | Clears all teams and resets game state |
| `/manhunt add runner <player>` | `manhunt.admin` | Adds a player as a Speedrunner |
| `/manhunt add hunter <player>` | `manhunt.admin` | Adds a player as a Hunter |
| `/manhunt remove <runner\|hunter> <player>` | `manhunt.admin` | Removes a participant |
| `/manhunt list` | `manhunt.admin` | Displays match status, dimensions, and teammate health |
| `/manhunt reload` | `manhunt.admin` | Reloads `config.yml` |

---

## 🔒 Server Licensing Notice

`manhuntK` operates under **Node-Locked IP:Port Server Licensing**.
Each server installation must be authorized by **Krishna Mittal**. Unauthorized servers attempting to run this plugin will automatically be shut down by the cloud verification system.

To license or transfer your server, contact the developer.

---

## 📄 License

Distributed under the MIT License. Copyright (c) 2026 Krishna Mittal.
