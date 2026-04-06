# Snake 2D

A classic Snake game implemented in Python using the Pygame library. Guide your snake to eat food, grow longer, and avoid collisions with walls and yourself!

## 🎮 Features

- **Classic Gameplay**: Control a snake that grows each time it eats food
- **Smooth Controls**: Responsive arrow key and WASD movement
- **Score Tracking**: Real-time score display showing how many foods you've eaten
- **Collision Detection**: Game ends when you hit walls or your own tail
- **Restart Functionality**: Quick restart after game over without restarting the application
- **Grid-Based Movement**: Traditional snake movement on a discrete grid

## 📋 Requirements

- Python 3.x
- Pygame library

## 🚀 Installation

1. **Clone or download this repository**

2. **Install Pygame**:
   ```bash
   pip install pygame
   ```

## ▶️ How to Run

Execute the game from your terminal:

```bash
python snake.py
```

## 🎯 Controls

| Key | Action |
|-----|--------|
| ↑ / W | Move Up |
| ↓ / S | Move Down |
| ← / A | Move Left |
| → / D | Move Right |
| SPACE | Restart (after game over) |
| ESC | Quit Game |

## 🎲 Gameplay

1. **Objective**: Eat the red food blocks to grow your snake and increase your score
2. **Movement**: Use arrow keys or WASD to change direction
3. **Growth**: Each food item eaten increases your snake's length by one segment
4. **Game Over**: The game ends if your snake:
   - Collides with the window boundaries (walls)
   - Collides with its own body
5. **Restart**: Press SPACE to start a new game after game over

## ⚙️ Game Specifications

- **Window Size**: 640 × 480 pixels
- **Grid Size**: 20 × 20 pixels per cell
- **Game Speed**: 10 FPS (frames per second)
- **Snake Color**: Green (RGB: 0, 255, 0)
- **Food Color**: Red (RGB: 255, 0, 0)
- **Background**: Black (RGB: 0, 0, 0)

## 🏗️ Project Structure

```
snake-game/
├── snake.py          # Main game script
├── README.md         # This file
└── requirements.txt  # Python dependencies (optional)
```

## 💡 Tips

- Plan your moves ahead to avoid trapping yourself
- Try to maintain space for maneuvering as your snake grows
- Avoid quick reversals - the snake cannot turn 180° instantly
- Practice smooth, controlled movements for high scores

## 🛠️ Customization

You can easily modify the game by editing `snake.py`:

- **Change speed**: Modify the `clock.tick(10)` value (higher = faster)
- **Adjust window size**: Change `WINDOW_WIDTH` and `WINDOW_HEIGHT` constants
- **Modify colors**: Update the RGB values in the color definitions
- **Resize grid**: Change `GRID_SIZE` constant

## 📝 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Feel free to fork this repository, make improvements, and submit pull requests!

---

**Enjoy playing Snake 2D! 🐍**
