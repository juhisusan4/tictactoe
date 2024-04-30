# Tic Tac Toe Game with GUI in Java

## Overview
This is a Java implementation of the classic Tic Tac Toe game with a graphical user interface (GUI). The game provides a more interactive experience compared to text-based versions, allowing players to make moves by clicking on the grid squares.

## Features
- Graphical User Interface: Players interact with the game using a visual grid displayed on the screen.
- Two-player mode: Players take turns clicking on empty grid squares to place their marks (X or O).
- Win detection: The game detects when a player has achieved three marks in a row and declares them as the winner.
- Draw detection: If all spaces on the grid are filled and no player has achieved three marks in a row, the game declares a draw.
- Restart functionality: Players can choose to restart the game after a win, loss, or draw.

## How to Play
1. Run the `TicTacToeGUI.java` file to start the game.
2. The game window will appear, displaying a 3x3 grid of squares.
3. Players take turns clicking on empty squares to place their marks.
4. The game will automatically detect win or draw conditions and display the result.
5. Players can choose to restart the game by clicking on a "Restart" button.

## Implementation Details
- The game logic is implemented in the `TicTacToe` class.
- The graphical user interface is built using Java Swing components.
- Event listeners are used to handle player clicks and update the game state accordingly.
- Win and draw conditions are checked after each player move.
- The game window is created and managed by the `TicTacToeGUI` class.

## Dependencies
- Java Development Kit (JDK) version X.X or higher.
- No external libraries are required.

## Future Improvements
- Enhancing the visual design of the game interface.
- Adding support for customizable player names.
- Implementing an AI opponent for single-player mode.
- Adding sound effects and animations to make the game more engaging.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
This project was created as a personal project and was inspired by various Tic Tac Toe GUI implementations available online.

