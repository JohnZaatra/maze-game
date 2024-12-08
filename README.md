# Maze Game Project

This project is a maze game implementation with a client-server architecture. It features algorithms for maze generation and solving, as well as a client-side application for interacting with the maze. Written entirely in Java, the project includes both a JAR file for execution and source code (`src` folder) containing core logic and GUI components.

## Project Structure

The project consists of the following main components:

- **algorithms**: Includes classes for maze generation and search algorithms.
- **Client**: Handles client-side logic and interactions with the maze.
- **IO**: Provides utilities for data compression and decompression.
- **Server**: Implements server-side logic for handling requests and managing strategies.
- **META-INF**: Contains metadata for the JAR file, including the manifest file.
- **src**: Contains the core source code for the application's logic and GUI.

### Main Classes in `src`:
- **Model**: Includes the business logic for managing the maze and its operations.
  - `IModel`: Interface for the model logic.
  - `MyModel`: Implementation of the model interface.
- **View**: Handles the graphical user interface (GUI) and user interaction.
  - `IView`: Interface for view components.
  - `Main`: The main entry point of the application.
  - `MazeDisplayer`: Custom GUI component to render the maze.
  - `MyViewController`: The primary controller managing user interaction with the maze.
  - `PropertiesController`: Handles user preferences and configurations.
- **ViewModel**: Acts as a bridge between the Model and View layers.
  - `MyViewModel`: Manages communication between the model and view components.

## Features

- **Maze Generation**: Generate different types of mazes using various algorithms.
- **Search Algorithms**: Solve mazes using DFS, BFS, or Best-First Search.
- **Client-Server Communication**: Clients can request maze generation and solving via a server.
- **Compression Utilities**: Compress and decompress maze data for efficient storage and transmission.
- **Graphical User Interface**: Intuitive GUI built with JavaFX for enhanced user experience.

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

You can run the project from IntelliJ IDEA or another Java IDE by setting the main class as View.Main (or the appropriate entry point for your application).

## Folder Structure

Here is an overview of the folder structure within the project:

   ``` bash
   Maze Game Project/
   ├── src/
   │   ├── Model/
   │   │   ├── IModel.java
   │   │   ├── MyModel.java
   │   ├── View/
   │   │   ├── IView.java
   │   │   ├── Main.java
   │   │   ├── MazeDisplayer.java
   │   │   ├── MyViewController.java
   │   │   ├── PropertiesController.java
   │   ├── ViewModel/
   │   │   ├── MyViewModel.java

   ├── ATPProjectJAR.jar
   │   ├── algorithms/
   │   │   ├── AMazeGenerator.java
   │   │   ├── BestFirstSearch.java
   │   │   ├── DepthFirstSearch.java
   │   │   ├── Maze.java
   │   │   └── ...
   │   ├── Client/
   │   │   ├── Client.java
   │   │   ├── IClientStrategy.java
   │   ├── IO/
   │   │   ├── MyCompressorOutputStream.java
   │   │   ├── SimpleCompressorOutputStream.java
   │   │   └── ...
   │   ├── META-INF/
   │   │   └── MANIFEST.MF
   │   ├── Server/
   │   │   ├── Server.java
   │   │   ├── ServerStrategyGenerateMaze.java
   │   │   └── ...
   ```

## Known Issues

- **Invalid URL Error**: Ensure that all resources (such as images) used by the application are correctly linked and exist in the project directory.
- **JavaFX Issues**: Make sure that JavaFX 23 is properly installed and configured if you're using it for the GUI.

## Project Context and Significance

This project was developed as part of my final course project in the fourth semester of my Information and System Engineering degree at Ben Gurion University in the Negev, Israel. It has been an incredibly rewarding experience, allowing me to apply theoretical knowledge in practical scenarios and develop a deeper understanding of software design and implementation.
Through this project, I honed my skills in Java programming, client-server architecture, and algorithm development. Working on features such as maze generation, search algorithms, GUI design, and data compression provided me with a comprehensive understanding of problem-solving and efficient system design.
This project serves as a testament to my technical abilities, creativity, and dedication to quality software engineering. By integrating these diverse elements into a single cohesive project, I demonstrated my ability to think critically and work effectively on complex systems. I believe this experience exemplifies my readiness to contribute meaningfully to professional development teams, and I am eager to bring this knowledge and passion to new opportunitiesץ
