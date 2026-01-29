# Maze

Welcome to the Maze repository! This project is a Java-based 2D maze application with a graphical user interface (GUI) that provides interactive maze generation and pathfinding capabilities.

## Overview

This application allows users to:
- Generate random mazes with customizable dimensions
- Generate mazes with guaranteed paths from start to exit
- Load mazes from text files
- Find and visualize the shortest path through a maze
- Interactive GUI built with Java Swing

## Features

- **Maze Generation**: Create mazes with rows and columns between 3-30
- **Guaranteed Path Mode**: Generates a maze that always has a valid path from start (S) to exit (X)
- **Random Maze Mode**: Creates a random maze configuration
- **File Input**: Load custom mazes from text files
- **Shortest Path Finding**: Automatically calculates and displays the shortest path through the maze
- **Visual Interface**: User-friendly GUI for all interactions

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your system
- Basic familiarity with running Java applications

### Running the Application

1. Compile the Java file:
   ```bash
   javac Maze.java
   ```

2. Run the application:
   ```bash
   java Maze
   ```

3. The GUI will launch, presenting options to either generate a maze or read one from a file.

## Usage

Upon launching the application, you'll be presented with two main options:

1. **Generate Maze**: Create a new maze by specifying rows and columns, then choose between:
   - Guaranteed Path Maze: Ensures a valid path exists
   - Random Maze: Creates a random configuration

2. **Read from File**: Load a maze from a text file following the expected format

After generating or loading a maze, use the "Find Shortest Path" button to visualize the solution.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

Please refer to the repository license for usage terms.
