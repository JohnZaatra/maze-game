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

1. From the command line: After building the project, you can run the JAR file directly:

   ```bash
   java -jar target/ATPProjectJAR.jar
   ```

2. From your IDE: You can run the project from IntelliJ IDEA or another Java IDE by setting the main class as View.Main (or the appropriate entry point for your application).


## Folder Structure

Here is an overview of the folder structure within the project:

   ``` bash
   ATPProjectJAR.jar
   ├── algorithms/
   │   ├── AMazeGenerator.java
   │   ├── BestFirstSearch.java
   │   ├── DepthFirstSearch.java
   │   ├── Maze.java
   │   └── ...
   ├── Client/
   │   ├── Client.java
   │   ├── IClientStrategy.java
   ├── IO/
   │   ├── MyCompressorOutputStream.java
   │   ├── SimpleCompressorOutputStream.java
   │   └── ...
   ├── META-INF/
   │   └── MANIFEST.MF
   ├── Server/
   │   ├── Server.java
   │   ├── ServerStrategyGenerateMaze.java
   │   └── ...
   └── ...
   ```

## Known Issues

- **Invalid URL Error**: Ensure that all resources (such as images) used by the application are correctly linked and exist in the project directory.
- **JavaFX Issues**: Make sure that JavaFX 23 is properly installed and configured if you're using it for the GUI.

## Project Context and Significance

This project was developed as part of my final course project in the fourth semester of my Information and System Engineering degree at Ben Gurion University in the Negev, Israel. It has been an incredibly valuable experience, not only in applying the knowledge I gained throughout my studies but also in developing a deep understanding of software design, algorithms, and the integration of complex systems. Throughout this project, I had the opportunity to sharpen my skills in Java development, problem-solving, and working with technologies like JavaFX for the graphical user interface. This project has allowed me to demonstrate my ability to think critically and creatively to develop efficient solutions. By integrating diverse elements such as algorithmic problem solving, client-server architecture, and data compression, this project exemplifies my readiness to contribute effectively to real-world challenges. I believe the skills I have developed here will be a strong asset to any team, and I am eager to bring my passion for technology and innovation to new opportunities in the field.
