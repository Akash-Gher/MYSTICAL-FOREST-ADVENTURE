
# MYSTICAL FOREST ADVENTURE - Slot Game using PIXI.js

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Game Components](#game-components)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This is a slot machine game built using **PIXI.js** for rendering graphics and animations. The game includes spinning reels, a preloader screen, and interactive UI elements such as bet controls, a spin button, and a modal popup for game info.

## Features
- Preloader with progress bar and animated logo.
- 3x5 slot reels with customizable symbols.
- Bet controls with increase/decrease buttons.
- Spin functionality with balance and win tracking.
- Game information popup (paytable) using a modal.
- Responsive design for different screen sizes.

## Prerequisites
Make sure you have the following installed:
- **Node.js** (v14 or higher)
- **npm** or **yarn** for managing dependencies.
- **Parcel** as the build tool.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/slot-game-pixi.git
   cd slot-game-pixi
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

   Parcel will automatically bundle your project and serve it on a local development server. You can view the game at `http://localhost:1234`.

## Usage
After starting the game, the preloader will show a progress bar. Once the loading is complete, click on the screen to enter the main game.

**Controls**:
- Use the left and right arrow buttons to adjust the bet amount.
- Click the **Spin** button to spin the reels.
- Click the **Info** button to view the paytable in a modal popup.

## Game Components
### 1. **Preloader**
   The preloader displays a progress bar and the game logo while assets are being loaded. Once the loading is complete, the player can click to enter the game.
   
### 2. **Reels**
   The game consists of 3 rows and 5 columns of symbols, which spin to determine the outcome of each play.

### 3. **Control Panel**
   - **Balance**: Displays the player's current balance.
   - **Bet Amount**: Adjust the bet amount using arrow buttons.
   - **Win Amount**: Displays the win amount after a spin.

### 4. **Modal Popup**
   A paytable modal that provides information about the game symbols and their corresponding rewards.

## File Structure
```
slot-game-pixi/
├── assets/                  # Contains images, sounds, and spritesheets
├── src/
│   ├── slot-game.js         # Main game logic
│   └── components/          # Reusable components like reels, UI, etc.
├── dist/                    # Built files after running Parcel
├── package.json             # Dependencies and scripts
└── README.md                # This file
```

## Contributing
If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repo.
2. Create your feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
