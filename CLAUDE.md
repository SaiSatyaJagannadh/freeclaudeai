# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple web-based implementation of the classic Nokia Snake game. The entire game is contained in a single HTML file (`index.html`) with embedded CSS and JavaScript.

## Development

### Running the Game

To run the game locally:
1. Open `index.html` in any modern web browser.
2. The game will start automatically; use arrow keys or WASD to control the snake.

### Development Workflow

Since this is a static HTML/CSS/JS project:
- Edit `index.html` directly to modify the game.
- Changes are visible immediately upon refreshing the browser.
- No build steps, dependencies, or tooling are required.

### Code Structure

The `index.html` file contains:
- **HTML structure**: Defines the game container, score display, and canvas.
- **CSS styles**: Styles for the game's Nokia phone aesthetic.
- **JavaScript game logic**: 
  - Game state (snake position, direction, food, bonus)
  - Game loop using `requestAnimationFrame`
  - Rendering functions for snake, food, bonus, and UI
  - Input handling for arrow keys and WASD
  - Game mechanics (collision detection, scoring, speed increase)

### Making Changes

1. **Game logic**: Modify the JavaScript within the `<script>` tag to change game mechanics.
2. **Styling**: Edit the CSS in the `<style>` tag to adjust visuals.
3. **HTML structure**: Update the markup if needed (though the structure is simple).

### Testing

There are no automated tests. To test changes:
1. Save changes to `index.html`.
2. Reload the page in your browser.
3. Play the game to verify behavior.

### Best Practices

- Keep changes within the single `index.html` file for simplicity.
- Maintain the Nokia aesthetic when modifying styles.
- Ensure game logic remains deterministic and frame-rate independent (uses delta time).
- The game uses local storage for high score persistence; avoid changing the storage key (`nokia_snake_hi`) unless intentionally breaking compatibility.

## Common Tasks

### Changing Game Difficulty
Modify these constants in the JavaScript:
- `BASE_TICK`: Initial game speed (ms per tick)
- `MIN_TICK`: Maximum speed (minimum ms per tick)
- `score*4`: Speed increase rate (currently `BASE_TICK - score*4`)

### Adding New Food Types
Edit the `FRUITS` array in the JavaScript to add new fruit objects with `pts` (points) and `color`/`stem` properties.

### Changing Canvas Size
Adjust `COLS`, `ROWS`, and `CELL` constants to change the grid size and cell dimensions.