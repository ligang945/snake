# 🐍 Snake Game

A modern, single-file HTML/CSS/JavaScript Snake game with multiple input methods and polished UI.

## Features

- **Canvas-based gameplay**: 30x30 grid with smooth rendering
- **Progressive difficulty**: Speed increases by 3ms per food eaten (minimum 80ms)
- **Smart food spawning**: Food appears at edges more often as score increases (up to 70% chance)
- **Multiple input methods**:
  - Keyboard (Arrow keys or WASD)
  - Mobile touch controls
  - Gamepad/controller support with haptic feedback
- **Audio effects**: Web Audio API for move, score, and game over sounds (toggleable)
- **High score persistence**: Saved to localStorage
- **Responsive design**: Adapts to mobile screens
- **Visual polish**: Snake eyes, food glow, animated message boxes

## How to Play

1. Click "Start Game" or press the Start button on your gamepad
2. Use arrow keys, WASD, or gamepad to change direction
3. Eat the red food to grow and score points (+10 per food)
4. Avoid hitting walls or your own body
5. Press Space or the Start button to pause

## Controls

- **Arrow Keys / WASD**: Change direction
- **Space**: Pause/Resume game
- **Gamepad**:
  - D-Pad or Left Stick: Change direction
  - Start Button: Start game or Pause/Resume

## Technical Details

- **Grid Size**: 30x30 tiles
- **Initial Speed**: 500ms per tick
- **Minimum Speed**: 80ms per tick
- **Speed Increase**: 3ms faster per food eaten
- **Food Edge Probability**: Scales from 0% to 70% based on score
- **Canvas Size**: 600x600px (scales with viewport)

## Browser Support

- Modern browsers with ES6 support
- Web Audio API support required for sound effects
- Gamepad API support required for controller input

## License

MIT
