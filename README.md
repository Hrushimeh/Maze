# 🍅 2D Maze Assignment 🍅

A Java-based interactive maze generator and solver application with a graphical user interface (GUI).

---

## 🍅 Table of Contents

🍅 [Features](#-features)  
🍅 [Getting Started](#-getting-started)  
🍅 [Usage](#-usage)  
🍅 [Technical Details](#-technical-details)  
🍅 [Requirements](#-requirements)  
🍅 [License](#-license)

---

## 🍅 Features

This maze application provides several powerful features:

🍅 **Generate Random Maze** - Create randomly generated mazes with customizable dimensions  
🍅 **Guaranteed Path Maze** - Generate mazes with a guaranteed solution path  
🍅 **Read from File** - Load custom mazes from text files  
🍅 **Shortest Path Finder** - Automatically find and display the shortest path from start to exit  
🍅 **Interactive GUI** - User-friendly graphical interface built with Java Swing  
🍅 **Customizable Size** - Configure maze dimensions (3x3 to 30x30)

---

## 🍅 Getting Started

### Prerequisites

🍅 Java Development Kit (JDK) 8 or higher  
🍅 Java Runtime Environment (JRE)

### Quick Start

1. 🍅 **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Maze
   ```

2. 🍅 **Compile the program**
   ```bash
   javac Maze.java
   ```

3. 🍅 **Run the application**
   ```bash
   java Maze
   ```

---

## 🍅 Usage

### Main Menu Options

When you launch the application, you'll be presented with two main options:

🍅 **Generate Maze** - Create a new maze using the built-in generator  
🍅 **Read from File** - Load a maze from a text file

### Generate Maze Mode

1. Select the number of rows and columns (3-30)
2. Choose between:
   - 🍅 **Guaranteed Path Maze**: Ensures a valid solution path exists
   - 🍅 **Random Maze**: Creates a random maze (may not have a solution)
3. Click "Find Shortest Path" to display the solution

### Read from File Mode

1. Enter the filename (without the .txt extension)
2. Click "Load Maze"
3. The maze will be validated and displayed
4. Click "Find Shortest Path" if a valid path exists

### Maze Symbols

🍅 **S** - Starting position (Mouse)  
🍅 **X** - Exit position  
🍅 **B** - Blocked/Border spaces  
🍅 **O** - Open spaces  
🍅 **/** - Shortest path indicator

---

## 🍅 Technical Details

### Maze Validation

The application validates maze data according to the following rules:

🍅 Rows and columns must be between 3 and 30  
🍅 Exit (X) must be on the border  
🍅 Starting position (S) must NOT be on the border  
🍅 No open spaces on borders  
🍅 Both mouse (S) and exit (X) must exist  
🍅 Maze dimensions must match the specified rows and columns

### Path Finding Algorithm

The application uses a shortest path algorithm to find the optimal route from the starting position to the exit, ensuring the most efficient solution is displayed.

---

## 🍅 Requirements

🍅 **Java Version**: JDK 8 or higher  
🍅 **Dependencies**: 
  - java.awt.*
  - java.awt.event.*
  - java.io.*
  - java.util.*
  - javax.swing.*

🍅 **Display**: GUI requires graphical display support

---

## 🍅 License

This project is available for educational purposes.

---

🍅 *Enjoy navigating through the maze!* 🍅
