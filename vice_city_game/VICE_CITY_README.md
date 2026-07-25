# Vice City - Basic Version

A simple 2D top-down game inspired by the Grand Theft Auto: Vice City experience, built with HTML, CSS, and JavaScript.

## Features

- Retro-inspired pixel art aesthetic with neon colors
- Open-world style navigation through Vice City streets
- Collect cash and avoid police and gangsters
- Wanted level system that increases with your score
- Health management with health pickups
- Score tracking based on survival time and collections
- Responsive controls (Arrow keys or WASD)
- Game over screen with statistics
- Restart functionality for endless gameplay

## How to Play

1. Open `vice_city_game.html` in any modern web browser
2. Click the "START GAME" button to begin
3. Use the arrow keys or WASD to move your character (the green circle)
4. Collect cash (green items) to earn money and points
5. Collect health (orange items) to restore your health
6. Collect weapons (purple items) for bonus points
7. Avoid police (blue enemies) and gangsters (red enemies)
8. Your wanted level increases as you score higher, bringing more aggressive enemies
9. Survive as long as possible to achieve the highest score!

## Controls

- **Arrow Keys** or **WASD**: Move your character
- **Objective**: Survive, collect items, avoid enemies
- **Game Over**: When your health reaches 0
- **Restart**: Click "PLAY AGAIN" after game over

## Game Mechanics

- **Health**: Starts at 100%, decreases when hit by enemies
- **Cash**: Collect cash items to increase your money
- **Score**: Increases based on survival time and collected items
- **Wanted Level**: Increases with score, bringing more police
- **Enemies**: 
  - Cops (blue): More aggressive, cause higher wanted level increase
  - Gangsters (red): Moderate threat
  - Civilians (gray): Minimal threat (included for ambiance)

## Technical Details

- Built with vanilla HTML5, CSS3, and JavaScript
- No external dependencies or frameworks
- Responsive design works on desktop and mobile browsers
- Uses requestAnimationFrame for smooth gameplay
- Simple collision detection system
- Procedural enemy and item spawning

## Files

- `vice_city_game.html`: Main game file
- Other files in this directory are the Claude Code agents that were created as requested

## Development

This game was created as a demonstration of what can be built with basic web technologies. It showcases:
- Game loop implementation
- Entity management (player, enemies, collectibles)
- Collision detection
- State management
- User input handling
- UI updates
- Game progression systems

## How to Run

Simply double-click the `vice_city_game.html` file or open it in your web browser:
```
open vice_city_game.html  # macOS
start vice_city_game.html # Windows
xdg-open vice_city_game.html # Linux
```

Or drag and drop the file into your browser window.

Enjoy your time in Vice City!