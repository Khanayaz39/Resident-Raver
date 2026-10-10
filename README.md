# Resident Raver 🎮

**Resident Raver** is a browser-based 2D platform shooter game developed using HTML5, CSS3, and vanilla JavaScript. The game uses the HTML5 Canvas API to render a pixel-art-style environment where players can move, jump across a tile-based map, and shoot zombie enemies.

## ✨ Features

- **Player Movement:** Move left and right with keyboard controls.
- **Jump Mechanics:** Jump using gravity-based physics.
- **Zombie AI:** Zombie enemies move horizontally and reverse direction when they hit walls.
- **Shooting System:** Fire bullets to eliminate zombies.
- **Collision Detection:** Detect collisions between the player, walls, bullets, and zombies.
- **Tile-Based Level:** A grid-based map defines walls, platforms, and open spaces.
- **Pixel-Art Graphics:** Procedurally embedded SVG sprites represent the player, zombies, walls, and bullets.
- **Automatic Respawn:** The player respawns when falling out of the game world or colliding with a zombie.
- **Browser-Based Gameplay:** Play directly in a modern web browser without installing additional software.

## 🛠️ Technologies Used

- **HTML5** — Game structure and Canvas element.
- **CSS3** — Dark theme, layout, and interface styling.
- **JavaScript (ES6+)** — Game logic, physics, input handling, and collision detection.
- **Canvas API** — Rendering the game world and entities.
- **SVG** — Lightweight, embedded game sprites.
- **requestAnimationFrame()** — Continuous game loop and rendering.

## 📁 Project Structure

```text
Resident-Raver/
├── index.html       # Game interface, styles, and JavaScript logic
└── README.md        # Project documentation
```

The current implementation contains the game logic and graphics directly in `index.html`, so no external asset files or JavaScript libraries are required.

## 🚀 Getting Started

### Prerequisites

- A modern web browser, such as Google Chrome, Microsoft Edge, or Firefox.
- No additional libraries, package managers, or build tools are required.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/resident-raver.git
   ```

2. Navigate to the project directory:

   ```bash
   cd resident-raver
   ```

3. Open `index.html` in your web browser.

Alternatively, download the repository as a ZIP file, extract it, and open `index.html`.

## 🎮 Controls

| Key | Action |
|---|---|
| `←` Left Arrow | Move left |
| `→` Right Arrow | Move right |
| `Z` | Jump |
| `Space` | Jump |
| `X` | Shoot |

## ⚙️ Game Mechanics

### Physics and Movement

The game implements basic platformer physics using gravity, horizontal acceleration, friction, and a maximum movement speed. Vertical velocity controls jumping and falling.

### Level Design

The game world is represented by a two-dimensional array. Each grid cell represents either a wall or open space. The collision system checks the player's and other entities' positions against this map.

### Enemies and Combat

Zombie enemies patrol the environment and reverse direction when they encounter walls. Players can shoot bullets to eliminate zombies. When the player touches a zombie, the player respawns at the starting position.

### Rendering

The game uses the HTML5 Canvas API to draw the map and update the player, zombies, and bullets. SVG sprites are embedded directly into the JavaScript code, eliminating the need for separate image assets.

## 🌐 Deployment

Resident Raver is a static web application and can be hosted using services such as:

- **GitHub Pages**
- **Render Static Sites**
- **Netlify**
- **Vercel**

For deployment on Render:

1. Push the project to a GitHub repository.
2. Open the [Render Dashboard](https://dashboard.render.com/).
3. Select **New → Static Site**.
4. Connect your GitHub repository.
5. Set the publish directory to the project root, where `index.html` is located.
6. Deploy the site and use the generated public URL to play the game.

**Note:** The game does not require a continuously running backend server. Once deployed as a static site, it can be accessed through its public URL without maintaining a Node.js server.

## 🔮 Future Enhancements

- Add multiple levels with increasing difficulty.
- Implement player health, lives, and a scoring system.
- Add zombie animations and additional enemy types.
- Introduce sound effects and background music.
- Add a start screen, pause menu, and game-over screen.
- Improve responsiveness for different screen sizes.
- Add collectible items, ammunition limits, and power-ups.

## 📄 License

This project is available for educational and personal use. Add a formal license file if you intend to distribute the source code under specific reuse conditions.

---

**Resident Raver** — A simple HTML5 platform shooter demonstrating game physics, collision detection, enemy movement, and real-time browser rendering.
