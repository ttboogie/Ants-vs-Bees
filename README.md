# Ants vs. SomeBees 🐜🐝

This project is a tower-defense style game created as part of a class project. In **Ants vs. SomeBees**, players strategically place different types of ants to defend their colony from waves of invading bees. Each ant type has unique abilities and costs, making strategy essential for protecting the colony. (Similar idea to Plants vs. Zombies).

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [How to Play](#how-to-play)
- [File Structure](#file-structure)

## Introduction

**Ants vs. SomeBees** is a graphical game where players control an ant colony under siege by bees. The game combines elements of strategy and resource management, requiring players to make decisions about which ants to place, where to place them, and when to replace them.

This project was developed as part of a course taken in the past, based on concepts taught in the course about programming, abstraction, and modularity.

## Features

- **GUI Interface**: Interact with the game through a graphical interface.
- **Multiple Ant Types**: Choose from a variety of ants, each with unique abilities, such as `Thrower Ant`, `Fire Ant`, `Ninja Ant`, and more.
- **Dynamic Bee Waves**: Face different bee types, including `Wasp`, `Hornet`, `Boss Bee`, and others with unique attributes.
- **Interactive Gameplay**: Strategically place ants to defend the colony and see how the waves of bees respond.

## Getting Started

### Prerequisites

- **Python**: Make sure Python is installed on your system.

### Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ttboogie/Ants-vs-Bees.git
   cd Ants-vs-Bees
   ```

2. **Run the Game**:
   Start the game by running `ants_gui.py`:
   ```bash
   python ants_gui.py
   ```

   This will open a graphical interface where you can play the game.

## How to Play

1. Launch the game using the command above.
2. Click on an ant from the control panel to select it.
3. Click on a location in the colony's tunnels to place the selected ant.
4. Watch as waves of bees attempt to invade the colony. Place ants strategically to defend the queen!

Each ant has a food cost, so you need to manage resources carefully. Some ants are good at attacking, while others provide defensive support. Experiment with different strategies to stop the bees from reaching the queen.

## File Structure

- `ants.py`: Contains the core game logic for ant and bee interactions.
- `ants_gui.py`: Implements the graphical user interface for the game.
- `ants_strategies.py`: Defines strategies that control the behavior of ants and bees.
- `graphics.py`: Contains functions for managing graphics and animations in the GUI.
- `utils.py`: Provides utility functions for the game.
- `img/`: Folder containing images for different game assets (e.g., ant and bee graphics).
- `tests/`: Folder with test files to check functionality (if applicable).
