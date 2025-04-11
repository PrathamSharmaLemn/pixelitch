# Pixelitch

**Pixelitch** is a top-down, pixel-art RPG inspired by classic monster-battling games like Pokémon. Developed using JavaScript and HTML5 Canvas, the game features a tile-based overworld and a foundational battle system. Players can explore the environment and engage in battles with default monsters.

> **Live Demo**: [Play Pixelitch on GitHub Pages](https://prathamsharmalemn.github.io/pixelitch/)

---

## Table of Contents

- [Features](#features)
- [Gameplay Overview](#gameplay-overview)
- [Technical Architecture](#technical-architecture)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Development Roadmap](#development-roadmap)

---

## Features

- **Tile-Based Exploration**: Navigate through a pixelated world using a grid-based movement system.
- **Monster Battles**: Engage in turn-based battles with default monsters.
- **HTML5 Canvas Rendering**: Smooth graphics rendering using the Canvas API.
- **Modular Codebase**: Organized and maintainable code structure for scalability.
- **Responsive Controls**: Keyboard input handling for seamless gameplay.

---

## Gameplay Overview

In its current iteration, Pixelitch allows players to:

- Move a character across a tile-based map.
- Encounter and battle a default monster using a basic attack system.

Future updates aim to introduce:

- Multiple monsters with unique abilities.
- Inventory and item management.
- Enhanced battle mechanics with status effects and abilities.
- Save and load game functionality.

---

## Technical Architecture

### Technologies Used

- **JavaScript (ES6+)**: Core game logic and interactivity.
- **HTML5 Canvas**: Rendering the game world and sprites.
- **CSS3**: Styling and layout.
- **GitHub Pages**: Hosting the live demo.

### Core Components

- **Game Loop**: Manages the update and render cycles.
- **Input Handler**: Captures and processes user input.
- **Renderer**: Draws game elements onto the canvas.
- **Entity System**: Manages game objects like players and monsters.
- **Battle System**: Handles combat logic and UI.

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari).
- [Git](https://git-scm.com/) installed on your machine.

### Installation

1. **Clone the Repository**

  ```bash
   git clone https://github.com/prathamsharmalemn/pixelitch.git
   ```
2. **Navigate to the Project Directory**

  ```bash
   cd pixelitch
  ```
3. **Open index.html in Your Browser**

You can open the file directly or use a local development server:

  ```bash
  # Using Python 3.x
  python -m http.server
  ```
Then, navigate to http://localhost:8000 in your browser.

### Project Structure

```plaintext
pixelitch/
├── assets/
│   ├── images/
│   │   ├── tileset.png
│   │   ├── player.png
│   │   └── monster.png
│   └── audio/
│       └── battle-theme.mp3
├── src/
│   ├── main.js
│   ├── gameLoop.js
│   ├── inputHandler.js
│   ├── renderer.js
│   ├── entities/
│   │   ├── player.js
│   │   └── monster.js
│   └── systems/
│       ├── battleSystem.js
│       └── mapSystem.js
├── index.html
├── styles.css
└── README.md
```
``` assets/: ``` Contains images and audio files.

``` src/: ``` Contains JavaScript source code organized into modules.

``` index.html: ``` The main HTML file.

``` styles.css: ``` Stylesheet for the game.

``` README.md: ``` Project documentation.

### Development Roadmap

 - Implement multiple monster types with unique stats.
 - Develop an inventory system for items.
 - Enhance battle mechanics with abilities and status effects.
 - Create a save/load game feature using localStorage.
 - Optimize for mobile devices with touch controls.
 - Add background music and sound effects.

