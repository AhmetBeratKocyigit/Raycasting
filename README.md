# 3D Raycasting Engine

This project is a simple implementation of a 3D raycasting engine using Python and the Pygame library. Raycasting is a technique used to create 3D world simulations.

## Introduction

Raycasting is a rendering technique used in computer graphics to create a 3D perspective in a 2D map. In this project, we simulate a 3D environment by casting rays from the player's viewpoint and rendering the scene accordingly.

## How It Works

The player navigates through the 3D environment using keyboard controls. Raycasting is used to calculate the distance from the player to the walls in the scene, which determines the height of the walls in the rendered view. The scene is then drawn on the screen using Pygame.

## Features

- Simple 3D environment simulation
- Player movement and rotation
- Basic wall rendering using raycasting

## Installation

### Prerequisites

- Python 3.x
- Pygame library

### Installation

1. Install Python from [Python's Official Website](https://www.python.org/downloads/).
2. Install Pygame by running `pip install pygame` in your terminal.

## Usage

1. Clone the repository or download the source code.
2. Navigate to the project directory using the terminal.
3. Run the command `python raycasting.py` to start the project.

## Controls

- Use the arrow keys to move forward, backward, and rotate left or right.
- Press the ESC key to exit the game.
