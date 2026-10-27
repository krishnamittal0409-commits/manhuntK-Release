# manhuntK 🧭

[![Minecraft Version](https://img.shields.io/badge/Minecraft-Paper%201.21.x-brightgreen.svg)](https://papermc.io)
[![Java Version](https://img.shields.io/badge/Java-21-blue.svg)](https://adoptium.net)
[![Latest Release](https://img.shields.io/github/v/release/krishnamittal0409-commits/manhuntK-Release?color=orange&label=Latest%20Version)](https://github.com/krishnamittal0409-commits/manhuntK-Release/releases/latest)
[![Discord](https://img.shields.io/badge/Discord-kzen__fights-5865F2?logo=discord&logoColor=white)](https://discord.com)

A modern, high-performance **Manhunt (Speedrunner vs Hunter)** plugin designed from the ground up for **Paper 1.21+** Minecraft servers.

---

## 📥 Official Download

> [!IMPORTANT]
> **Download the Latest Protected JAR:**  
> 👉 **[Download manhuntK.jar (Latest Release)](https://github.com/krishnamittal0409-commits/manhuntK-Release/releases/latest)**

*Note: Older releases are automatically retired upon each new release to ensure all servers run the most up-to-date, secure version.*

---

## ✨ Features

* **Universal Interactive GUI (`/mhgui` for Everyone):**
  * All players (non-op and op alike) can run `/mhgui` to open the sleek 45-slot dashboard.
* **Player Self-Team Selection & Admin Lock Hierarchy:**
  * Before the match begins, players can pick and switch their own teams (Hunters or Speedrunners).
  * **Operator Lock Protection:** If an operator (OP) assigns or locks a player (`/manhunt add` or `/manhunt lock`), that player's team is locked and cannot be changed by the player. Only an OP can change or unlock them.
  * **Mid-Game Security:** Once the match starts, normal players cannot change teams or start/stop the match. Only operators have mid-game team reassignment and match control privileges.
* **Multi-Speedrunner & Multi-Hunter Compatibility:** Play with any number of hunters and runners simultaneously.
* **Modern In-Game Radar Menu:**
  * Right-click your tracking compass to open an interactive chest GUI displaying all alive speedrunners' real player skin heads.
  * Live distance meter and dimension indicators (`Overworld 🌿`, `The Nether 🔥`, `The End 🌌`).
  * 1-click lock needle onto any speedrunner.
* **Random Seed & In-Game World Reset:**
  * Reset worlds directly from the game! One click wipes `world`, `world_nether`, and `world_the_end`, writes a brand new random seed, and restarts the server cleanly.
* **Teammate-Only Health Visibility:**
  * Hunters can only see fellow Hunters' live health. Enemy speedrunner health is hidden (`???`).
  * Speedrunners can only see fellow Speedrunners' live health.
* **Cross-Dimension Compass Tracking:**
  * Uses modern Paper 1.21 Lodestone tracking coordinates (works across Overworld, Nether, and End).
  * Automatically points to the speedrunner's last portal exit when in different dimensions.
* **Auto-Refreshing Radar:** Compass needle recalculates automatically every 5 seconds (100 ticks).
* **Automatic Update Alerts:** Server administrators receive in-game pings whenever a new update is released.

---

## 📜 Commands Reference

| Command | Permission | Description |
| :--- | :--- | :--- |
| `/mhgui` *(or `/manhunt menu`)* | **Everyone** | Opens the modern interactive GUI control center |
| `/compass` | `manhunt.compass` *(default: all)* | Retrieves or refreshes your tracking radar compass |
| `/manhunt list` | **Everyone** | Displays match status, team rosters, locks, and dimensions |
| `/manhunt start` | `manhunt.admin` *(op)* | Starts the match and equips hunters with compasses |
| `/manhunt stop` | `manhunt.admin` *(op)* | Halts tracking and pauses the game |
| `/manhunt reset` | `manhunt.admin` *(op)* | Clears all teams, locks, and resets game state |
| `/manhunt add <runner\|hunter> <player>` | `manhunt.admin` *(op)* | Assigns and locks a player to a team |
| `/manhunt remove <runner\|hunter> <player>` | `manhunt.admin` *(op)* | Removes and unlocks a participant |
| `/manhunt lock <player>` | `manhunt.admin` *(op)* | Locks a player's team so they cannot switch |
| `/manhunt unlock <player>` | `manhunt.admin` *(op)* | Unlocks a player's team so they can self-select |
| `/manhunt newseed` | `manhunt.admin` *(op)* | Opens confirmation to wipe worlds and restart with a random seed |
| `/manhunt reload` | `manhunt.admin` *(op)* | Reloads `config.yml` |

---

## 💬 Licensing & Contact

`manhuntK` uses **Node-Locked IP:Port Server Licensing** to protect against unauthorized redistribution.

To purchase a license, activate your server, or request a host transfer:
* **Discord:** **`kzen_fights`** (Kzen)
* **Email:** `krishnamittal0409@gmail.com`

> **⚡ Quick 3-Step Activation Guide:**  
> 1. Download `manhuntK.jar` and drop it into your server's `plugins/` folder.  
> 2. Start the server once. Your console will print your **Server Address** (e.g. `147.135.38.12:25565`).  
> 3. Send that address to **`kzen_fights`** on Discord to get your server activated in seconds!

---

## 📄 License

Distributed under the MIT License. Copyright (c) 2026 Krishna Mittal.
