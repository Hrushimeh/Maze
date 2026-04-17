# 🍅🍅🍅 Maze Generator & Solver 🍅🍅🍅🍅

A Java-based maze generation and solving application with an interactive GUI interface.

---

## 🍅 Table of Contents

🍅 [Features](#-features)  
🍅 [Getting Started](#-getting-started)  
🍅 [Usage](#-usage)  
🍅 [Technical Details](#-technical-details)  
🍅 [Requirements](#-requirements)  

---

## 🍅 Features

🍅 **Random Maze Generation**: Create randomly generated mazes with customizable dimensions  
🍅 **Guaranteed Path Mazes**: Generate mazes with a guaranteed solution path from start to exit  
🍅 **Shortest Path Finding**: Automatically finds and displays the shortest path through the maze  
🍅 **File Import**: Load custom maze configurations from text files  
🍅 **Interactive GUI**: User-friendly graphical interface built with Java Swing  
🍅 **Customizable Dimensions**: Support for mazes ranging from 3x3 to 30x30  

---

## 🍅 Getting Started

### Prerequisites

🍅 Java Development Kit (JDK) 8 or higher  
🍅 Java Runtime Environment (JRE)  

### Quick Start

1. **Compile the application**:
   ```bash
   javac Maze.java
   ```

2. **Run the application**:
   ```bash
   java Maze
   ```

---

## 🍅 Usage

### Main Menu Options

The application provides two primary modes of operation:

🍅 **Generate Maze**: Create a new random or guaranteed-path maze  
🍅 **Read from File**: Import a maze from a text file  

### Generating a Maze

1. Enter the desired number of rows (3-30)
2. Enter the desired number of columns (3-30)
3. Choose between:
   - 🍅 **Guaranteed Path Maze**: Ensures a solvable path exists
   - 🍅 **Random Maze**: Generates a random maze that may or may not be solvable

### Finding the Shortest Path

🍅 Click the "Find Shortest Path" button to visualize the solution  
🍅 The path will be displayed on the maze grid  
🍅 If no path exists, you'll receive a notification  

### Maze Legend

🍅 **S** - Starting position (Mouse)  
🍅 **X** - Exit position  
🍅 **B** - Border/Blocked spaces  
🍅 **O** - Open spaces  
🍅 **/** - Shortest path markers  

---

## 🍅 Technical Details

### Algorithm

The application uses pathfinding algorithms to:
- 🍅 Generate mazes with guaranteed solvable paths
- 🍅 Find the shortest path from start to exit
- 🍅 Validate maze configurations

### File Format

When importing mazes from files, ensure:
- 🍅 Rows and columns are specified correctly (3-30)
- 🍅 Starting position (S) is not on the border
- 🍅 Exit position (X) is on the border
- 🍅 Legend matches the expected format
- 🍅 No open spaces on borders (except exit)

---

## 🍅 Requirements

### System Requirements

🍅 **Java Version**: JDK 8 or higher  
🍅 **Display**: GUI-capable environment  
🍅 **Memory**: Minimum 512 MB RAM  

### Development

🍅 Java Swing library (included in JDK)  
🍅 Java AWT library (included in JDK)  

---

🍅 **Enjoy solving mazes!** 🍅
