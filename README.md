# Maze

A Java-based 2D maze application with a graphical user interface (GUI) that allows users to generate and solve mazes.

## Features

- **Generate Maze**: Create custom mazes with user-specified dimensions (3-30 rows and columns)
  - Guaranteed Path Maze: Generates a maze with a guaranteed solution path
  - Random Maze: Generates a maze with randomized obstacles
- **Read from File**: Load maze configurations from text files
- **Shortest Path Finder**: Automatically calculates and displays the shortest path from start to exit
- **Interactive GUI**: Built with Java Swing for an intuitive user experience

## Requirements

- Java Development Kit (JDK) 8 or higher
- Java Runtime Environment (JRE)

## Usage

### Compilation

```bash
javac Maze.java
```

### Running the Application

```bash
java Maze
```

## Maze Components

- **S**: Starting position (mouse)
- **X**: Exit position
- **B**: Blocked/border spaces
- **O**: Open spaces
- **/**: Shortest path (when displayed)

## Maze Dimensions

- Minimum size: 3x3
- Maximum size: 30x30
