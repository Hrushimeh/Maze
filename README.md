# 🧩 2D Maze Solver

A Java-based interactive maze solver application with a graphical user interface (GUI) that allows users to generate mazes and find the shortest path from start to exit.

## ✨ Features

- 🎲 **Random Maze Generation**: Create randomly generated mazes with customizable dimensions
- 🛤️ **Guaranteed Path Maze**: Generate mazes with guaranteed solvable paths
- 📁 **File Import**: Load maze configurations from text files
- 🔍 **Pathfinding Algorithm**: Find and display the shortest path from mouse (S) to exit (X)
- 🖼️ **Interactive GUI**: User-friendly graphical interface built with Java Swing
- ⚙️ **Customizable Dimensions**: Support for mazes ranging from 3x3 to 30x30

## 🚀 Getting Started

### Prerequisites

- ☕ Java Development Kit (JDK) 8 or higher
- 💻 Java Runtime Environment (JRE)

### 📦 Installation

1. Clone the repository or download the source code
2. Navigate to the project directory
3. Compile the Java file:
```bash
javac Maze.java
```

### ▶️ Running the Application

Execute the compiled program:
```bash
java Maze
```

## 🎮 Usage

### Main Menu Options

When you launch the application, you'll be presented with two main options:

1. **🎨 Generate Maze**: Create a new maze with custom dimensions
   - Choose between Random Maze or Guaranteed Path Maze
   - Specify rows and columns (3-30)
   - Click "Find Shortest Path" to visualize the solution

2. **📂 Read from File**: Load a maze from a text file
   - Enter the filename (without .txt extension)
   - The maze will be loaded and displayed
   - Find the shortest path if one exists

### 🗺️ Maze Components

- **S** (Mouse): Starting position 🐭
- **X** (Exit): Goal/Exit position 🚪
- **B** (Border/Block): Blocked spaces/walls 🧱
- **O** (Open): Passable spaces ⬜
- **/** (Path): Shortest path indicator 🛤️

## 📝 File Format

When reading mazes from files, ensure your file follows the correct format:
- First line: Legend definitions (BORD, O, MOUSE, EXIT, B)
- Second line: Number of rows and columns
- Following lines: The maze matrix

## 🔧 Technical Details

### Key Methods

- `generateMaze()`: Creates a maze with guaranteed solvable path
- `formMaze()`: Generates a random maze
- `findShortestPath()`: Implements pathfinding algorithm to find the shortest route
- `addMazePanel()`: Displays the maze in the GUI
- `loadMazeButton()`: Handles file input for maze loading

### 🏗️ Architecture

The application uses:
- Java Swing for GUI components
- Recursive pathfinding algorithms
- 2D array representation for maze structure
- Event-driven programming with ActionListeners

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs
- 💡 Suggest new features
- 🔀 Submit pull requests

## 📄 License

This project is available for educational and personal use.

## 🙏 Acknowledgments

Built as a 2D Maze Assignment demonstrating:
- Data structure implementation
- Algorithm design
- GUI development in Java
- File I/O operations
