🏰 Arcade Castle Defense Strategy Game in Python (University Project)

2D arcade-style strategy game developed in **Python** using the **Pygame** library. The player must defend a mighty castle from waves of bloodthirsty monsters, upgrade defenses, and survive through increasing levels of difficulty.

## 🎯 Objective

As the defender of the castle, your mission is to **repel incoming enemy waves**, prevent the castle from being destroyed, and complete as many levels as possible. With each wave, enemies become stronger and more numerous.

## 🛠 Technologies Used

The project was developed in **PyCharm Community Edition** using the following Python modules:

- [`pygame`](https://www.pygame.org/) — for game logic, rendering, sound, and event handling.
- `random` — for generating randomized enemy appearances and events.
- `os` — for file system operations like saving the high score.
- `math` — for calculating projectile angles and enemy movements.

## 🧱 Main Components

- **Castle** — the main base that must be protected.
- **Towers** — additional defenses that can be built using coins.
- **Enemies** — animated hostile units with attack, walk, and death actions.
- **Bullets** — projectiles fired by the player or towers.
- **Buttons** — UI elements to control upgrades: repair, armor, build towers.
- **Crosshair** — allows aiming and shooting via mouse.

## 🎮 Gameplay

- Earn **coins and score** for defeating enemies.
- Spend coins on **repairs**, **armor upgrades**, and **building towers**.
- Each new level increases the **number and strength of enemies**.
- If the castle’s health reaches zero, the game is over.
- Replayable levels with increasing difficulty.
