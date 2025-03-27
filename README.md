
# Tetris Game in C++

A  Tetris Game implementation in C++ using console graphics.

## Table Of Contents
- [Features](#Features)
- [Requirements](#Requirements)
- [Installation](#Installation)
- [Controls](#Controls)
- [Game Mechanics](#Game-Mechanics)
- [Scoring System](#Scoring-System)
- [Sample Photo](#Sample-Photo)

## Features

- Tetris gameplay with 7 different tetromino shapes
- Score system with high score tracking
- Colorful console interface
- Keyboard controls for movement and rotation
- Game speed increases as you play

## Requirements

- MacOS
- C++ compiler (tested with g++ or any standard-compliant compiler)
- Standard C++ libraries: `<iostream>`, `<vector>`, `<locale.h>`, `<unistd.h>`, `<cstdlib>`, `<ctime>`

## Installation

1. Clone this repository or download the source files
2. Compile the code using your preferred C++ compiler: g++ -std=c++11 tetris.cpp -lncurses
3. Run the executable: ./tetris


## Controls

| Key          | Action               |
|--------------|----------------------|
|       A      | Move piece left      |
|       D      | Move piece right     |
|       S      | Soft drop (move down)|
|       W      | Rotate piece         |
|       P      | Pause                |
|       Q      | Quit game            |
|       G      | Hold Piece           |
|       R      | Resume               |

## Game Mechanics

- Pieces spawn at the top center of the playfield
- Complete lines to score points and clear space
- Game ends when new pieces can't spawn
- Score increases based on number of lines cleared at once

## Scoring System

- 1 line: 100 points

## Sample Photo 




