# Rooftop Cat

## Description

**Rooftop Cat** is a browser-based endless runner game where a cat runs across city rooftops during a storm. Your goal is to avoid obstacles, stay alive, and travel as far as possible while chasing a higher score.

Each run is different because obstacles are generated randomly. The game is built with HTML Canvas and vanilla JavaScript, so it does not require a game engine, installation, or external dependencies.

## How to Play

1. Open `RooftopCat.html` in any modern web browser.
2. Choose one of the six cat avatars: Orange, Black, White, Calico, Siamese, or Tuxedo.
3. Jump over boxes, gaps, and ledges as you run across the rooftops.
4. Use any of these controls to jump:
   - Press `Space` or `Arrow Up` on the keyboard.
   - Tap anywhere on a mobile or touch device.
   - Click anywhere on the game canvas.
5. You can perform up to three jumps in a row. The jump count resets when the cat lands.
6. Use the pause button in the top-right corner to pause the game.
7. The run ends if the cat hits a box or falls from the rooftop. Select `run again` to start over.

## Scoring

- Your score is measured as distance in meters, such as `250 m`.
- The longer you survive, the higher your score becomes.
- An achievement notification appears every `1000 m`.
- Your best score is saved in the browser's `localStorage` and remains available for future runs in the same browser.
- The game gradually becomes faster as your distance increases.

## Features

- Endless rooftop running gameplay
- Six playable cat avatars
- Keyboard, mouse, and touch controls
- Triple-jump system
- Randomly generated obstacles
- Pause and restart options
- Distance score and persistent high score
- Milestone achievements every 1000 meters
- Night city background, stars, and simple sound effects
- No external libraries or build steps required

## How to Run

No installation is required.

1. Download or clone this repository.
2. Open `RooftopCat.html` in a web browser.
3. Choose a cat and start running.

## Project Structure

```text
RooftopCat/
├── RooftopCat.html   # Complete game with HTML, CSS, and JavaScript
└── readme.md         # Game description and playing guide
```

## Technologies

- HTML5
- CSS3
- JavaScript
- HTML Canvas API
- Web Audio API
- Browser Local Storage
