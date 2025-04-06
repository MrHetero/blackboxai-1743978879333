
Built by https://www.blackbox.ai

---

```markdown
# WASD Adventure Game

## Project Overview
WASD Adventure is a fun and engaging web-based game where players navigate a character using the WASD keys to collect coins and avoid enemies. The game features an animated and colorful interface, utilizing the Tailwind CSS framework and custom styles to enhance user experience. Players can also track their score and achieve high scores, which are saved in local storage.

## Installation
To run the WASD Adventure Game locally, follow these simple steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/wasd-adventure.git
   cd wasd-adventure
   ```
   
2. **Open the `index.html` file:**
   Open the `index.html` file in your preferred web browser. You can simply double-click the file or open it using the browser's file menu.

## Usage
- **Controls:**
  - Use the **W** key to move up.
  - Use the **A** key to move left.
  - Use the **S** key to move down.
  - Use the **D** key to move right.
  
- **Objective:**
  - Collect as many coins as you can while avoiding enemies. The game increases in difficulty as you progress.

- **Starting/Replaying the Game:**
  - To start, click the **START GAME** button.
  - After a game over, click the **PLAY AGAIN** button to restart.

## Features
- Intuitive movement controls using the WASD keys.
- Dynamic scoring system that rewards players for collecting coins.
- Difficulty progression that increases as players spend more time in the game.
- Local high score tracking in the browser.
- Vibrant visuals with neon text and particle effects.

## Dependencies
This project utilizes:
- **Tailwind CSS** for styling:
  - Included via CDN in the `index.html` file.

No additional JavaScript libraries or frameworks are used.

## Project Structure
The project consists of the following files:
```
.
├── index.html        # Main HTML file containing game logic and UI
```

### Key Components in `index.html`:
- **HTML Structure**: Contains the game canvas, score displays, and start/game over screens.
- **JavaScript**: Handles game logic, rendering, updates, and input controls.
- **CSS**: Inline styles and Tailwind CSS for responsive design and aesthetics.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements or bug fixes.

## License
This project is open-source and available under the MIT License.
```