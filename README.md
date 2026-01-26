# Hello! Welcome to Maze 👋

A Java-based 2D maze generator and solver with an interactive GUI. This application allows users to generate random mazes or create mazes with guaranteed solvable paths, and then find the shortest path through them.

## About

Maze is an educational project that demonstrates pathfinding algorithms and maze generation techniques. The application provides a visual, interactive experience for exploring maze generation and solving algorithms through a user-friendly graphical interface.

### Features

- **Two Generation Modes:**
  - **Guaranteed Path Maze**: Generates a maze with a guaranteed solvable path from start to exit
  - **Random Maze**: Creates a randomly generated maze that may or may not have a solution

- **Interactive GUI**: Built with Java Swing for an intuitive user experience
- **Shortest Path Finding**: Visualizes the shortest path from the starting position (mouse) to the exit
- **Flexible Dimensions**: Create mazes with custom dimensions (3-30 rows and columns)
- **File Import**: Load mazes from text files with custom configurations

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- A Java IDE (Eclipse, IntelliJ IDEA, NetBeans) or command-line tools

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Hrushimeh/Maze.git
   cd Maze
   ```

2. Compile the Java file:
   ```bash
   javac Maze.java
   ```

3. Run the application:
   ```bash
   java Maze
   ```

### Usage

1. **Launch the Application**: Run the `Maze` class to open the main window

2. **Choose Your Mode**:
   - Select "Generate Maze" to create a new maze interactively
   - Select "Read from file" to load a maze from a text file

3. **Generate Maze Options**:
   - Enter the desired number of rows (3-30)
   - Enter the desired number of columns (3-30)
   - Choose between "Guaranteed Path Maze" or "Random Maze"

4. **Find the Path**: Click "Find Shortest Path" to visualize the solution

### Maze File Format

When loading a maze from a file, use the following format:
- `S` - Starting position (mouse)
- `X` - Exit position
- `B` - Blocked/border spaces
- `O` - Open spaces

## Building and Development

### Project Structure

```
Maze/
├── Maze.java       # Main application file with GUI and maze logic
└── README.md       # This file
```

### Key Components

- **Maze Generation**: Randomized maze creation with configurable dimensions
- **Pathfinding Algorithm**: Shortest path calculation using graph traversal
- **GUI Interface**: Java Swing-based interactive interface
- **File I/O**: Read maze configurations from text files

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Open a Pull Request

Please ensure your code follows Java coding conventions and includes appropriate comments.

## License

This project is available as open source. Please check the repository for license information or contact the maintainer for clarification.

## Support and Contact

- **Repository**: [https://github.com/Hrushimeh/Maze](https://github.com/Hrushimeh/Maze)
- **Issues**: Report bugs or request features through GitHub Issues
- **Discussions**: Use GitHub Discussions for questions and community support

## Acknowledgments

This project was created as an educational tool for learning about:
- Maze generation algorithms
- Pathfinding and graph traversal
- Java GUI development with Swing
- Data structures and algorithms

---

**Happy Maze Solving! 🎯**
