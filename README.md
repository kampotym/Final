# Memory Game (4x4)

This is a classic memory game where players need to find matching pairs of cards. The game consists of 16 cards (8 pairs) that must be revealed, and if the cards match, they stay open. The game ends when all the pairs are found.

## Project Goals

- **Develop DOM manipulation skills**: Using JavaScript to dynamically create elements and manipulate them.
- **Learn JavaScript fundamentals**: Using events, array handling, timers, and functions to implement the game logic.
- **Create an interactive interface**: Implementing visual effects for user interaction.

## Features

1. **Game Start**:
   - When the "New Game" button is clicked, a new game begins.
   - Cards are generated randomly and displayed on the game board.
   - All cards are hidden initially, then shown for a few seconds before the game starts.

2. **Game Mechanics**:
   - Players flip over two cards at a time.
   - If the cards match, they stay open.
   - If the cards do not match, they are flipped back after a short delay.
   - The game ends when all pairs are found.

3. **Timer**:
   - The time spent on the game is tracked and displayed on the screen. The timer updates every second.

4. **Victory**:
   - When all pairs are found, a victory message appears on the screen.

## Technologies

- **HTML** for the structure of the page.
- **CSS** for styling and creating a responsive layout.
- **JavaScript** for the game logic (card generation, click handling, timer, etc.).

## Project Structure

- `index.html` — The main HTML file where the game's interface is defined.
- `style.css` — The CSS file containing styles for the game.
- `script.js` — The JavaScript code implementing the game logic.

## User Guide

### How to Play:

1. Open the `index.html` file in your browser.
2. Click the **"New Game"** button to start a new game.
3. Cards with symbols will be revealed. Your goal is to find all pairs of matching cards.
4. To do this, click on two cards in turn.
5. If the cards match, they will remain open.
6. If the cards do not match, they will be flipped back after a short delay.
7. The game ends when all pairs are found. A victory message will be shown.

### Example Gameplay:

- At the beginning, all cards are hidden.
- You click on the first card, then on the second. If the cards match, they stay open.
- If the cards are different, they will be flipped back after a short delay, and you continue to search for more pairs.

### Notes:
- The time spent on the game is tracked, and after you win, the number of seconds will be displayed.
- To start a new game, simply click the **"New Game"** button.

## Interface Example

The page displays:
- **Game Title** and a brief description.
- **Game Board** with the cards.
- **Timer** to track the time.
- **"New Game"** button to start a new game.
- **Victory Message** after all pairs are found.

## Installation and Setup

1. Download or clone the repository:
   
2. Open the `index.html` file in any browser.

3. Enjoy the game!

## Development

If you want to make changes to the project, follow these steps:

1. Edit the HTML, CSS, or JavaScript files as desired.
2. Run the game in your browser to check how your changes affect the gameplay.
3. Make a pull request if you'd like to share your changes.



