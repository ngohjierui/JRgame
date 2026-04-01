# EcoDefenders — Sustainability Tower Defense

**EcoDefenders** is a vibrant, educational tower defense game built with **HTML5, CSS3, and Vanilla JavaScript**. Designed for players aged 8 and up, it combines classic strategy gameplay with core environmental science concepts. Players must protect Earth from personified environmental threats using sustainable technologies as "towers."

---

## 🕹️ Gameplay Features

* **Six Unique Eco-Towers**:
    * **Forests (🌳)**: Absorb $CO_2$ enemies.
    * **Solar Panels (☀️)**: Slow down pollution clouds.
    * **Wind Turbines (🌬️)**: Provide knockback support.
    * **Recycling Centers (♻️)**: Convert waste enemies.
    * **Water Wetlands (💧)**: Slow and weaken incoming threats.
    * **Pollinators (🐝)**: Generate passive energy (currency).
* **Hero Progression**: Select from 6 classes (e.g., Forest Keeper, Climate Scientist, Urban Farmer) to gain specific damage and resource bonuses.
* **Educational Quests**: Complete in-game challenges like "Solar Pioneer" or "Green Guardian" to earn XP and unlock digital rewards.
* **Eco-Library**: A dedicated learning hub where players can discover facts about renewable energy, biodiversity, and carbon sequestration.
* **Dynamic Wave System**: Face escalating waves of threats, including Smog Crawlers, Plastic Waves, Carbon Blobs, and Industrial Dozers.

---

## 🛠️ Technical Stack

* **Engine**: Custom 2D Canvas API engine.
* **Logic**: Pure Vanilla JavaScript (No external frameworks/libraries).
* **Styling**: Modern CSS3 using Flexbox, Grid, and CSS Variables for a responsive, mobile-first UI.
* **Typography**: Integrated Google Fonts (*Nunito* and *Fredoka One*).

---

## 🚀 Quick Start

Since this is a client-side web application, there is no installation required.

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/yourusername/EcoDefenders.git](https://github.com/yourusername/EcoDefenders.git)
    ```
2.  **Open the file**:
    Simply double-click `EcoDefenders.html` to run the game in any modern web browser.

---

## 🗺️ Project Structure

* **`#hud`**: Tracks lives (❤️), Energy (⚡), XP (⭐), and Wave progress.
* **`#game-canvas`**: Handles the rendering of the S-shaped path, towers, projectiles, and particle effects.
* **`G`**: The global state object managing game variables, tower definitions, and enemy scaling logic.
* **`WAVE_DEFS`**: Contains the balancing parameters for enemy counts and spawn intervals.

---

## 🌿 Educational Impact

The game is designed to reinforce several key sustainability pillars:
* **Renewable Energy**: Understanding the roles of Solar and Wind.
* **Waste Management**: Highlighting the energy-saving benefits of recycling.
* **Biodiversity**: Emphasizing the importance of pollinators and wetlands.
* **Climate Mitigation**: Explaining how urban trees and forests act as carbon sinks.

---

## 📄 License

This project is open-source. Feel free to fork, modify, and use it for educational purposes.

> *“The greatest threat to our planet is the belief that someone else will save it.”* – **Robert Swan**

---

**Current Version**: 1.0.0
**Build Date**: April 2026
