# Snake Game

>>>>>> Introduction <<<<<<<<
This is a simple Snake Game implemented using HTML, CSS, and JavaScript. The game allows the player to control a snake to eat food, grow longer, and avoid collisions with the snake itself and the game boundaries.

## Files
- **index.html**: Contains the HTML structure of the game.
- **style.css**: Defines the styling for the game elements.
- **script.js**: Contains the JavaScript code for the game logic.

-----> How to Play ???<--------
1. Open the `index.html` file in a web browser.
2. The game will start automatically, and you control the snake using arrow keys (Up, Down, Left, Right).
3. The objective is to eat the food (displayed as a different colored square) to grow the snake and increase your score.
4. Avoid collisions with the snake itself and the game boundaries.

## Game Features ***
- **Scoring**: Each time the snake eats food, the player's score increases.
- **Speed Increment**: The snake's speed increases as the score goes up.
- **Game Over**: The game ends if the snake collides with itself or the game boundaries. A game over sound is played, and the player can restart by pressing any key.

## High Score
- The player's high score is stored locally using `localStorage`.
- If the player beats their high score, it is updated and displayed.

## Audio
- The game includes various audio files for eating, game over, moving, and background music.

## Customization
- You can customize the game by adjusting constants like `speedIncrement` and initial snake coordinates.
- Audio files can be replaced with your own.

## Dependencies
- None. The game is built using basic web technologies (HTML, CSS, JavaScript) and does not require any external libraries.


## Acknowledgments
- This game template is a simple implementation and can be used as a starting point for building more complex games.

## Functionality

### `main(ctime)`
- The main game loop that continuously updates the game state and renders the game.

### `isCollide(snake)`
- Checks for collisions, both with the snake itself and the game boundaries.

### `gameEngine()`
- Updates the snake array and food, checks for collisions, and handles game-over scenarios.

### Event Listeners
- `window.requestAnimationFrame(main)`: Initiates the game loop.
- `window.addEventListener('keydown', e => {...})`: Listens for arrow key presses to control the snake's direction.

### Initialization
- Sets up initial game state, including the snake, food, and high score.

### Audio Handling
- Uses HTML5 Audio objects to play sounds for eating, game over, moving, and background music.

### Score Update
- Updates the score and high score elements on the screen.

### Display
- Dynamically creates and updates HTML elements to display the snake, food, and other game elements.

## Styling

### Stylesheet
- The game uses a custom font called 'New Tegomin' imported from Google Fonts.
- The overall styling includes a background image, score display, grid layout for the game board, and styling for the snake, food, and game elements.

### Class Selectors
- `.head`: Styling for the snake's head, including a background gradient and a scaled appearance.
- `.snake`: Styling for the snake's body segments.
- `.food`: Styling for the food element, including an emoji representation.

### Background Image
- The game background is set using the `background` property with a linear gradient.

### Emoji for Food
- The food element is represented by an apple emoji ("🍎").



