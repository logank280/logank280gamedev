# Hi, I'm Logan (Dude7271)
### Roblox developer & CS Student at UNB

I am a Computer Science student and developer specializing in **backend systems**, **modular architecture**, and **secure data management** on Roblox. I treat game development with the same rigor as software engineering, utilizing professional workflows (Rojo, Git) to build scalable, maintainable codebases.

---

## Technical Skills

| **Languages** | **Frameworks & Libraries** | **Tools & Workflow** |
| :--- | :--- | :--- |
| ![Luau](https://img.shields.io/badge/Luau-00A2FF?style=flat&logo=lua&logoColor=white) **Luau** | **ProfileStore** (Data) | **Rojo** (External Sync) |
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) **Java** | **DataStore2** (Legacy Data) | **Git / GitHub** |
| ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) **C** | **Modular Architecture** | **Visual Studio Code** |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) **Python** |  | **Wally** (Package Manager) |

---

## Featured Projects

### 1. Custom Placement Tycoon System (OOP)
A highly scalable Tycoon fram5ework that allows for easy addition of new objects without rewriting core logic.
* **Core Mechanics:** Handles Spawners, Conveyors, Upgraders, and Collectors as distinct classes inheriting from a base `Object` class.
* **Logic System:** Includes a `LogicHandler` for "Wire" and "Gate" objects, allowing players to build complex logic circuits (AND/OR/XOR) to automate their tycoons.
* **Placement Validation:** Grid-based placement system (`PlacementValidator`) that handles rotation, collision detection, and plot boundaries.

<img width="553" height="307" alt="image" src="https://github.com/user-attachments/assets/5962b210-055a-48af-9b8d-3fd5148671ea" />
<img width="553" height="307" alt="image" src="https://github.com/user-attachments/assets/699bd429-4c35-4002-bcd9-de1309c21f42" />

### 2. Simulator Economy & Inventory Backend

A robust backend for a collection-style simulator game. Designed to handle secure transactions and inventory syncing.
* **Data Management:** Utilizes a custom wrapper for `DataStoreService` to handle complex player profiles, including "Berries Collected," "Items Owned," and "Areas Unlocked".
* **Shop Architecture:** Server-authoritative purchase validation system (`MarketplaceService` integration) that prevents exploiters from acquiring items without currency.
* **Analytics:** Integrated `AnalyticsManager` to track economy sinks and sources (Gold earned vs. Gold spent) to balance the game economy.

<img width="553" height="307" alt="image" src="https://github.com/user-attachments/assets/7b25d742-59d5-4733-96cf-58bbd16fdc3a" />

### 3. Procedural Terrain Generator
A script utilizing **Perlin Noise** (`math.noise`) to generate infinite, chunk-based terrain.
* **Biome Logic:** Automatically assigns materials (Sand, Grass, Slate) and colors based on the Y-level height map.
* **Asset Population:** Procedurally spawns trees and vegetation based on seed randomization, ensuring a unique map every time.

<img width="553" height="307" alt="image" src="https://github.com/user-attachments/assets/9b945a1d-8c59-46b3-a4aa-9df41155ad8a" />


### 4. Competitive Obby Framework
A stage-based progression system designed for speedrunning and competitive play.
* **Stage Persistence:** Uses `DataStore2` for ultra-reliable saving of stage progress and death counts.
* **Discord Integration:** Features a `DiscModule` to send Webhook notifications to a Discord server when players reach milestones or join the game.
* **Custom Intro UI:** A fully scripted camera intro sequence with tweened UI elements for a polished user experience.

<img width="553" height="307" alt="image" src="https://github.com/user-attachments/assets/fc302198-5008-4692-b301-23c41de55147" />


---

## 📬 Contact
* **Roblox:** Dude7271
* **Discord:** logank.280
---
