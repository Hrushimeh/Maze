# Hello! Welcome to Maze 🎯

A Java-based 2D maze generator and solver with an interactive graphical user interface. This application allows users to generate random mazes with guaranteed or random paths, load mazes from files, and find the shortest path through any maze.

## 📋 Description

This repository contains a comprehensive maze generation and solving application built with Java Swing. The Maze application provides an intuitive GUI that enables users to:

- **Generate Mazes**: Create random mazes with customizable dimensions (3x3 to 30x30)
- **Guaranteed Path Mazes**: Generate mazes with a guaranteed solution path
- **Random Mazes**: Create randomly generated mazes with or without solutions
- **Find Shortest Path**: Automatically calculate and display the shortest path from start to exit
- **Load from File**: Import custom maze configurations from text files
- **Interactive Visualization**: Visual representation of mazes with distinct markers for borders, open spaces, starting positions, and exits

## 🚀 Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Java Runtime Environment (JRE)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Hrushimeh/Maze.git
   cd Maze
   ```

2. Compile the Java source file:
   ```bash
   javac Maze.java
   ```

3. Run the application:
   ```bash
   java Maze
   ```

### Usage

1. **Launch the Application**: Run the compiled Maze class to open the main menu
2. **Choose an Option**:
   - **Generate Maze**: Create a new maze with custom dimensions
     - Enter the number of rows (3-30)
     - Enter the number of columns (3-30)
     - Select either "Guaranteed Path Maze" or "Random Maze"
     - Click "Find Shortest Path" to visualize the solution
   - **Read from File**: Load a pre-defined maze from a text file
     - Enter the filename (without .txt extension)
     - Click "Load Maze" to import the maze
     - Click "Find Shortest Path" to see the solution

### Maze Format

When loading mazes from files, use the following format:
- `S` - Starting position (mouse)
- `X` - Exit position
- `B` - Border/blocked spaces
- `O` - Open spaces
- Dimensions must be between 3x3 and 30x30
- Starting position must not be on the border
- Exit must be on the border

## 🎨 Features

- **Dual Generation Modes**: Choose between guaranteed solvable mazes or random mazes
- **Customizable Dimensions**: Select maze size from 3x3 up to 30x30
- **Shortest Path Algorithm**: Implements pathfinding to display optimal solutions
- **File Import**: Load custom maze designs from text files
- **Visual Feedback**: Clear visual indicators for maze elements and solutions
- **Error Validation**: Comprehensive input validation and error handling

## 🏗️ Project Structure

```
Maze/
├── Maze.java           # Main application file containing all maze logic and GUI
└── README.md          # This file
```

## 📖 Documentation

The application uses Java Swing for the graphical interface and implements:
- **Action Listeners**: For button interactions and user input
- **Grid Layouts**: For maze visualization
- **Pathfinding Algorithms**: For calculating shortest paths
- **File I/O**: For loading custom maze configurations

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure your code follows Java best practices and includes appropriate comments.

## 📝 License

This project is available as-is for educational purposes. Please check with the repository owner for specific licensing terms.

## 📧 Contact & Support

- **Repository**: [https://github.com/Hrushimeh/Maze](https://github.com/Hrushimeh/Maze)
- **Issues**: For bugs or feature requests, please open an issue on the GitHub repository

## 🙏 Acknowledgments

- Built with Java Swing for cross-platform GUI support
- Implements classic maze generation and pathfinding algorithms
- Designed for educational purposes and programming practice

---

**Happy Maze Solving!** 🧩✨
