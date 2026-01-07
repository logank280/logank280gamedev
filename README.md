# Hi, I'm Logan Kelly 👋
### Roblox Gameplay Engineer & CS Student at UNB

I am a Computer Science student and Gameplay Engineer specializing in **backend systems**, **modular architecture**, and **secure data management** on Roblox. I treat game development with the same rigor as software engineering, utilizing professional workflows (Rojo, Git) to build scalable, maintainable codebases.

This repository (`logank280gamedev`) is dedicated to my Luau projects and Roblox mechanics.
> *For my academic work in C, Java, and Python, please visit: [github.com/logank280projects](https://github.com/logank280projects)*

---

## 🛠️ Technical Skills

| **Languages** | **Frameworks & Libraries** | **Tools & Workflow** |
| :--- | :--- | :--- |
| ![Luau](https://img.shields.io/badge/Luau-00A2FF?style=flat&logo=lua&logoColor=white) **Luau** | **ProfileStore** (Data) | **Rojo** (External Sync) |
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) **Java** | **DataStore2** (Legacy Data) | **Git / GitHub** |
| ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) **C** | **Modular Architecture** | **Visual Studio Code** |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) **Python** |  | **Wally** (Package Manager) |

---

## 🚀 Featured Projects

### 1. Modular Tycoon System (OOP)
A highly scalable Tycoon framework built using **Object-Oriented Programming (OOP)** and Metatables. This system allows for easy addition of new objects without rewriting core logic.
* **Core Mechanics:** Handles Spawners, Conveyors, Upgraders, and Collectors as distinct classes inheriting from a base `Object` class.
* **Logic System:** Includes a `LogicHandler` for "Wire" and "Gate" objects, allowing players to build complex logic circuits (AND/OR/XOR) to automate their factories.
* **Placement Validation:** Grid-based placement system (`PlacementValidator`) that handles rotation, collision detection, and plot boundaries.
* **Tech Stack:** Luau, OOP, CollectionService.

![Tycoon Placement Demo](<img width="1106" height="624" alt="image" src="https://github.com/user-attachments/assets/89699789-1a8b-42de-a916-a05aa0dfccac" />)
### 2. Simulator Economy & Inventory Backend

A robust backend for a collection-style simulator game. Designed to handle secure transactions and inventory syncing.
* **Data Management:** Utilizes a custom wrapper for `DataStoreService` to handle complex player profiles, including "Berries Collected," "Items Owned," and "Areas Unlocked".
* **Shop Architecture:** Server-authoritative purchase validation system (`MarketplaceService` integration) that prevents exploiters from acquiring items without currency.
* **Analytics:** Integrated `AnalyticsManager` to track economy sinks and sources (Gold earned vs. Gold spent) to balance the game economy.

![Shop System Demo](PLACEHOLDER_LINK_TO_GIF_OR_IMAGE_HERE)
### 3. Procedural Terrain Generator
A script utilizing **Perlin Noise** (`math.noise`) to generate infinite, chunk-based terrain.
* **Biome Logic:** Automatically assigns materials (Sand, Grass, Slate) and colors based on the Y-level height map.
* **Asset Population:** Procedurally spawns trees and vegetation based on seed randomization, ensuring a unique map every time.

![Procedural Terrain](PLACEHOLDER_LINK_TO_GIF_OR_IMAGE_HERE)
### 4. Competitive Obby Framework
A stage-based progression system designed for speedrunning and competitive play.
* **Stage Persistence:** Uses `DataStore2` for ultra-reliable saving of stage progress and death counts.
* **Discord Integration:** Features a `DiscModule` to send Webhook notifications to a Discord server when players reach milestones or join the game.
* **Custom Intro UI:** A fully scripted camera intro sequence with tweened UI elements for a polished user experience.

![Obby System](PLACEHOLDER_LINK_TO_GIF_OR_IMAGE_HERE)

---

## 📬 Contact
* **Roblox:** [YourRobloxUsername]
* **Discord:** [YourDiscordHandle]
* **Email:** [YourEmail@example.com]

---
*Note: This portfolio features code snippets and systems developed for various personal and commission projects.*
