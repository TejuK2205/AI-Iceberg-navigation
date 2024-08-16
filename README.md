 # Iceberg Navigation System

This project implements an Iceberg Detection and Navigation System designed to enhance maritime safety by guiding ships around icebergs. The system uses computer vision for iceberg detection and an A* pathfinding algorithm for optimal navigation.

## Features

- **Iceberg Detection**: Utilizes image processing techniques to identify icebergs in the navigation path.
- **Pathfinding with A* Algorithm**: Calculates the safest and most efficient route around detected icebergs.
- **Interactive Visualization**: Real-time visualization of the navigation path within the grid system.

## Project Structure

- `iceberg.ipynb`: Jupyter Notebook containing all the code for iceberg detection and navigation, including the implementation of the A* pathfinding algorithm.
- `other files`: Files containing image assets used for visual representation (e.g., iceberg images, selection graphics).
- `matrix`: Represents the navigation grid where `1` indicates an iceberg and `0` indicates a navigable path.

## Dependencies

- `pygame`: Used for creating the interactive graphical interface.
- `pathfinding`: Provides the A* algorithm for pathfinding.
  
  Install the dependencies using pip:

  ```bash
  pip install pygame pathfinding

## How It Works

1. **Grid Setup**: The navigation area is divided into a grid where each cell represents either water or an iceberg.
2. **Pathfinding**: The A* algorithm finds the shortest path from a predefined starting point to a destination, avoiding cells marked as icebergs.
3. **Visualization**: The Pygame interface allows you to visualize the navigation path and interact with the system by clicking to set destinations.

## Usage

1. **Run the Project**: Open and run the `iceberg.ipynb` file in a Jupyter Notebook environment.
2. **Interactive Navigation**:
   - Left-click on the Pygame window to set the destination.
   - Press the `Space` key to clear the current path.
   - The grid will update the ship’s path based on the A* algorithm, avoiding icebergs and selecting the optimal route.

## Tech Stack

- **Python**: Core programming language used for algorithm implementation and logic.
- **Jupyter Notebook**: Development environment for code and documentation.
- **Pygame**: Library for creating the interactive graphical user interface and visualization.
- **Pathfinding Library**: Utilized for implementing the A* pathfinding algorithm.

