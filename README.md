# 🌟 2D Maze Generator & Solver 🎯

[![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)](https://www.java.com/) [![Swing](https://img.shields.io/badge/GUI-Swing-blue)](https://docs.oracle.com/javase/tutorial/uiswing/) [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## 📋 Description

A feature-rich **Java Swing application** that generates and solves 2D mazes with an intuitive graphical user interface! This project combines algorithms, GUI design, and pathfinding to create an interactive maze experience. Whether you want to generate a random maze or load one from a file, this application has you covered! 🚀

### ✨ Key Features

- 🎲 **Random Maze Generation**: Create unpredictable mazes with varying complexity
- 🛤️ **Guaranteed Path Mazes**: Generate mazes with guaranteed solutions from start to exit
- 📂 **File Loading**: Import custom mazes from text files
- 🔍 **Shortest Path Finder**: Uses advanced pathfinding algorithms to discover optimal routes
- 🎨 **Interactive GUI**: User-friendly interface built with Java Swing
- ⚙️ **Customizable Dimensions**: Configure maze size between 3x3 and 30x30
- 🖱️ **Click-to-Solve**: Find paths with a simple button click

## 🎯 How It Works

The application provides two main operational modes:

### 1️⃣ Generate Maze Mode 🏗️

Create mazes dynamically with configurable parameters:
- 📏 Specify rows and columns (3-30 range)
- 🎰 Choose between random or guaranteed path generation
- 🐭 Starting position (marked as 'S')
- 🚪 Exit position (marked as 'X')
- 🧱 Borders and obstacles (marked as 'B')
- 🌿 Open spaces (marked as 'O')

### 2️⃣ Read from File Mode 📖

Load pre-designed mazes from text files:
- 📝 Custom maze configurations
- 🔤 Configurable legend support
- ✅ Built-in data validation
- 🔍 Automatic error checking

## 🚀 Getting Started

### 📦 Prerequisites

Before running the application, ensure you have:

- ☕ **Java Development Kit (JDK)** version 8 or higher
- 💻 **Java Runtime Environment (JRE)**
- 🖥️ A system supporting GUI applications

### 🔧 Installation

1️⃣ **Clone the repository**:
```bash
git clone <repository-url>
cd Maze
```

2️⃣ **Compile the Java file**:
```bash
javac Maze.java
```

3️⃣ **Run the application**:
```bash
java Maze
```

## 📖 Usage Guide

### 🎮 Running the Application

When you start the program, you'll see a main menu with two options:

#### 🎲 Option 1: Generate Maze

1. 🖱️ Click on **"Generate Maze"** button
2. 📝 Enter the number of rows (3-30)
3. 📝 Enter the number of columns (3-30)
4. 🎯 Choose maze type:
   - **Guaranteed Path Maze** 🛤️: Ensures a valid solution exists
   - **Random Maze** 🎰: Creates a random layout (may not have a path)
5. 👁️ View the generated maze
6. 🔍 Click **"Find Shortest Path"** to visualize the solution

#### 📂 Option 2: Read from File

1. 🖱️ Click on **"Read from file"** button
2. 📝 Enter the filename (without .txt extension)
3. 📥 Click **"Load Maze"** to import the maze
4. 👁️ View the loaded maze
5. 🔍 Click **"Find Shortest Path"** to see the optimal route

### 📝 File Format

When creating custom maze files, follow this format:

```
<rows> <columns>
<legend>
S = Start position
X = Exit position
B = Border/Blocked space
O = Open space
<maze_layout>
```

## 🛠️ Technical Details

### 🏗️ Architecture

The application uses:
- 🖼️ **Java Swing** for GUI components
- 🎨 **BorderLayout** and **FlowLayout** for panel organization
- 🔄 **Action Listeners** for event handling
- 📊 **2D Arrays** for maze representation
- 🧮 **ArrayList** for path tracking

### 🧩 Core Components

- 🎯 **Maze Class**: Main application controller extending JFrame
- 🔍 **findShortestPath()**: Pathfinding algorithm implementation
- 🎨 **addMazePanel()**: GUI rendering for maze display
- 🏗️ **generateMaze()**: Maze generation algorithm
- 📂 **loadMazeButton()**: File loading and validation
- ✅ **Data Validation**: Input verification and error handling

### 🔑 Maze Symbols

| Symbol | Meaning | Emoji |
|--------|---------|-------|
| S | Start (Mouse position) | 🐭 |
| X | Exit | 🚪 |
| B | Border/Blocked | 🧱 |
| O | Open space | 🌿 |
| / | Shortest path | 🛤️ |

## 🎨 Features Breakdown

### ✅ Data Validation

The application performs comprehensive validation:

- ✔️ Rows and columns within 3-30 range
- ✔️ Maze dimensions match input specifications
- ✔️ Valid file existence checks
- ✔️ Exit position on border verification
- ✔️ Start position not on border
- ✔️ No open spaces on borders
- ✔️ Required mouse and exit positions exist
- ✔️ Correct legend format

### 🎯 Pathfinding Algorithm

- 🔍 Implements depth-first search (DFS) based approach
- 📊 Uses visited array to prevent cycles
- 📈 Tracks shortest path dynamically
- ⚡ Efficient recursive implementation
- 🎯 Finds optimal solution when path exists

## 🤝 Contributing

We welcome contributions! 💪 Here's how you can help:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m '✨ Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🔄 Open a Pull Request

### 💡 Ideas for Contributions

- 🎨 Enhance GUI design and user experience
- ⚡ Optimize pathfinding algorithms (A*, Dijkstra's)
- 📱 Add export functionality for solutions
- 🎬 Implement animation for path discovery
- 🎮 Add difficulty levels
- 🌈 Support for colored themes
- 📊 Statistics tracking (time, steps, etc.)

## 🐛 Known Issues & Limitations

- ⚠️ Maze size limited to 30x30 for performance
- ⚠️ Random mazes may not always have valid paths
- ⚠️ File format must be strictly followed
- ⚠️ GUI requires graphical environment

## 📚 Resources & References

- 📖 [Java Swing Documentation](https://docs.oracle.com/javase/tutorial/uiswing/)
- 🔍 [Pathfinding Algorithms](https://www.redblobgames.com/pathfinding/a-star/introduction.html)
- 🎮 [Maze Generation Algorithms](https://en.wikipedia.org/wiki/Maze_generation_algorithm)
- 💻 [Java AWT Documentation](https://docs.oracle.com/javase/8/docs/api/java/awt/package-summary.html)

## 📜 License

This project is available under the MIT License. See the LICENSE file for more details. 📄

## 👏 Acknowledgments

- 🙏 Thanks to all contributors
- 💡 Inspired by classic maze games
- 🎓 Educational project demonstrating algorithms and GUI programming

## 📞 Support & Contact

- 🐛 **Report bugs**: Open an issue on GitHub
- 💬 **Questions**: Start a discussion
- ⭐ **Like the project?**: Give it a star!

## 🎓 Learning Outcomes

This project demonstrates:

- 🧠 **Algorithm Design**: Pathfinding and maze generation
- 🎨 **GUI Development**: Event-driven programming with Swing
- 📊 **Data Structures**: 2D arrays, ArrayLists, boolean matrices
- ✅ **Input Validation**: Robust error handling
- 🏗️ **Software Architecture**: Object-oriented design patterns
- 📂 **File I/O**: Reading and parsing text files

## 🚧 Future Enhancements

Planned features for future releases:

- 🎯 Multiple maze generation algorithms
- 🎨 Enhanced visual effects and animations
- 💾 Save/load maze configurations
- 🏆 Leaderboard for fastest solutions
- 🎮 Interactive maze editing
- 🌐 Web-based version
- 📱 Mobile app support

---

Made with ❤️ and ☕ | Happy Maze Solving! 🎉

🌟 **Star this repository if you found it helpful!** 🌟
