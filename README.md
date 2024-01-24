# Snake and Ladders Game

## Overview

The Snake and Ladders Game is a Python implementation of the classic board game using the Turtle graphics library. The game features a 5x5 grid with snakes and ladders that players navigate using a dice roll. The goal is to reach the last tile first.

## Features

1. **Board Setup:**
    - A 5x5 grid is created using the Turtle graphics library, serving as the game board.
    - Tiles are numbered, and snakes and ladders are positioned on specific tiles.

2. **Player Characters:**
    - Two player characters, represented by a bull and a cow, move across the board based on dice rolls.

3. **Dice Roll Display:**
    - A graphical representation of a dice roll is displayed using Turtle graphics.

4. **Snakes and Ladders:**
    - Snakes and ladders are placed on specific tiles, affecting player movement.

5. **Turn System:**
    - Players take turns rolling the dice and moving across the board.

6. **Winning Screen:**
    - A winning screen is displayed when one of the players reaches the last tile.

## Functionality

### Grid Creation

The game board is created using the Turtle graphics library. The grid consists of 5x5 tiles, and the `GridDirections` function is used to draw the grid lines.

### Tile Numbering

The `TileNumber` function labels each tile with a corresponding number, making it easier for players to track their progress.

### Snakes and Ladders

Snakes and ladders are placed on specific tiles using the `RunDrawObject` function. Each snake or ladder is represented by an image drawn on the Turtle canvas.

### Dice Display

The `Dice2` function initializes the position and shape of the dice, registering different images for each dice roll. The `MoveSize` function generates a random dice roll between 1 and 6.

### Image Registration

Images of the bull and cow are registered and assigned to player characters using the `bull` and `cow` functions. These characters are displayed on the Turtle canvas.

### Winning Screen

The `WinningScreen` function displays a winning screen when one of the players reaches the last tile.

### Turn System

The `TurnSystem` function implements the game's turn system. Players take turns rolling the dice and moving their respective characters across the board. Snakes and ladders influence movement.

### Board Reset

The `BoardReset` function resets the game board, hides the winning screen, and prepares for a new game.

## First Run of Code

The initial setup of the game involves creating the board, numbering tiles, placing snakes and ladders, setting up the dice, initializing player characters, and starting the turn system. The game continues until one player reaches the last tile, triggering the winning screen. Players can choose to play again by pressing Enter.

## Planned Enhancements

1. **Menu System:**
    - Implement a menu system with options to start a new game, choose player characters, and access additional features.
    
2. **Multiple Difficulty Levels:**
    - Add support for multiple difficulty levels, adjusting the complexity of snake and ladder placements.

3. **Enhanced Graphics:**
    - Improve the visual appeal of the game by adding animations and better graphics.

4. **Settings and Customization:**
    - Add options for players to customize the game settings, such as board size and the number of snakes and ladders.
