# Moving Object Game with Snippiness Effect 

A fun, interactive browser game where the player controls a moving object that must avoid randomly moving obstacles. Upon crashing into an obstacle, the main object breaks into smaller fragments (snippiness effect) before the game ends.

## Live Demo
You can play the game here: [Live Game](https://nishattandra.github.io/ObjectMoving-webgl/)

## Features

- **Player Control**: Control the main object using the arrow keys to move in different directions.
- **Obstacles**: Randomly moving obstacles with varying speeds and sizes.
- **Collision Detection**: The game ends when the player collides with an obstacle, triggering an explosion-like snippiness effect.
- **Score System**: Keep track of your score and try to beat the high score.
- **Responsive Design**: The game automatically adjusts to fit the size of your browser window.

## Snippiness Effect

When the main object crashes into an obstacle, it shatters into smaller fragments that scatter across the screen. The fragments gradually fade away, adding a cool visual effect to the game-over sequence.

## How to Play

1. **Start the Game**: Click on the "Start Game" button to begin.
2. **Move the Player**: Use the arrow keys to move the player:
   - `Up Arrow`: Move up
   - `Down Arrow`: Move down
   - `Left Arrow`: Move left
   - `Right Arrow`: Move right
3. **Avoid Obstacles**: The goal is to avoid the moving obstacles that bounce around the screen.
4. **Game Over**: If you crash into an obstacle, the game ends with a snippiness effect. Your final score is displayed, along with the high score.
5. **Play Again**: Click on the "Play Again" button to restart the game.

## How to Run the Game

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nishattandra/ObjectMoving-webgl.git
   cd moving-object-game
