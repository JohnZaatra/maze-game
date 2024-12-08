# Maze Game Project

This project is a maze game implementation with a client-server architecture. It includes algorithms for maze generation and searching, as well as a client-side application to interact with the maze. The game logic is written in Java, and the project is packaged into a JAR file that can be executed to play the game.

## Project Structure

The project consists of the following main components:

- **algorithms**: Contains classes for maze generation and searching algorithms.
- **Client**: The client-side application, including the logic for interacting with the maze.
- **IO**: Includes classes for data compression and decompression.
- **Server**: Contains server-side logic for handling communication and various server strategies.
- **META-INF**: Metadata for the JAR file, including the manifest file.

### Main Algorithm Classes:
- **Maze Generation**: Various classes for generating mazes (`AMazeGenerator`, `MyMazeGenerator`, etc.).
- **Search Algorithms**: Includes depth-first search, breadth-first search, best-first search (`DepthFirstSearch`, `BreadthFirstSearch`, `BestFirstSearch`).
- **SearchableMaze**: Represents the structure of the maze that can be searched.

## Features

- **Maze Generation**: Generate different types of mazes using various algorithms.
- **Search Algorithms**: Use different algorithms (DFS, BFS, Best-First Search) to solve the maze.
- **Client-Server Communication**: A client can connect to the server to request a maze to be generated and solved.
- **Compression**: Compress and decompress maze data for efficient storage and transmission.

## Requirements

- **Java 23** or higher
- **JavaFX 23** SDK for GUI (if applicable)
- Maven (optional, for dependency management)

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/maze-game.git
   ```

2. Navigate to the project directory:

   ```bash
   cd maze-game
   ```

3. If using Maven for dependency management, run the following command to download the required dependencies:

   ```bash
   mvn install
   ```

4. Build the project to generate the JAR file:

   ```bash
   mvn package
   ```

Alternatively, you can use your IDE to build the project.

## Running the Project

