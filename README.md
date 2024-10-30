# Simon Game

A simple implementation of the classic Simon memory game using HTML, CSS, and jQuery. This game challenges players to follow an increasing sequence of colors and sounds, testing their memory and concentration.

## Table of Contents

- [How to Play](#how-to-play)
- [Code Overview](#code-overview)
- [Dependencies](#dependencies)

## How to Play

1. Press any key to start the game.
2. Follow the sequence of button presses and match the pattern that appears.
3. The pattern sequence gets longer with each successful level.
4. If you press a wrong button, the game ends, and you can restart by pressing any key again.

## Code Overview

The game is implemented in JavaScript using jQuery. Here's a breakdown of the main functions:

- `nextSequence()`: Generates a new random color, updates the game sequence, and displays it to the player.
- `checkAnswer(currentLevel)`: Checks the player's input against the game pattern to determine if it is correct.
- `startOver()`: Resets the game state when the player makes a mistake.
- `playSound(name)`: Plays a sound associated with the color chosen.
- `animatePress(currentColor)`: Animates button presses.

### Main Variables

- `buttonColours`: Array of possible color options.
- `gamePattern`: Array storing the randomly generated pattern.
- `userClickedPattern`: Array storing the player's input.
- `level`: Stores the current level.
- `started`: Boolean to track if the game has started.

Dependencies
jQuery is used to handle DOM manipulation and event handling.
