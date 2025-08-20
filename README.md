
# Pac-Man Java Game


A classic implementation of the iconic Pac-Man game using Java's AWT and Swing libraries. This project serves as both a functional game and an educational resource, demonstrating fundamental game development concepts such as game loops, collision detection, and event handling.

## 🎮 Features

- **Classic Gameplay**: Navigate Pac-Man through a maze, eat pellets, and avoid ghosts.
- **Tile-Based Maze**: The game world is represented as a grid, with walls, pellets, and power-ups.
- **Ghost Behavior**: Four ghosts with distinct movement patterns add challenge.
- **Scoring System**: Earn points by consuming pellets and power-ups.
- **Power-Ups**: Special items that grant Pac-Man temporary abilities.
- **Level Progression**: Advance through levels with increasing difficulty.

## 🛠️ Technologies Used

- **Java AWT & Swing**: For GUI components and event handling.
- **Java 2D Graphics**: To render game elements.
- **Timer**: To manage game updates and frame rate.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Java Development Kit (JDK)
- Visual Studio Code (VS Code) or any preferred IDE
- Git (optional, for cloning the repository)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Jamrahc/Pacman-Java.git
   cd pacman-java
   ```

2. Open the project in your IDE.

3. Run the `App.java` file to start the game.

## 🧩 How It Works

### Game Loop

The game operates on a continuous loop, updating the game state and rendering the screen at regular intervals. This loop handles:

- Player input (arrow keys)
- Ghost movement
- Collision detection
- Scoring updates
- Level transitions

### Game Components

- **App.java**: The entry point of the game, setting up the main window and initiating the game loop.
- **PacMan.java**: Contains the game logic, including movement, collision detection, and rendering.
- **Ghost.java**: Defines the behavior and movement patterns of the ghosts.
- **TileMap.java**: Represents the maze layout and handles map rendering.

### Controls

- **Arrow Keys**: Move Pac-Man up, down, left, or right.
- **Esc**: Pause or resume the game.

## 🔧 Future Enhancements

Potential improvements include:

- Implementing power-ups that allow Pac-Man to eat ghosts.
- Adding sound effects and music.
- Creating custom levels with different layouts.
- Enhancing AI for ghost movement.

