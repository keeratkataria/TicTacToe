
## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).


Tic-Tac-Toe (Java Swing)
🎯 Overview
A classic two-player Tic-Tac-Toe game built with Java Swing. Features include:

Interactive 3×3 game board.

Automated win/tie detection with visual feedback.

Score tracking for X and O players.

"Restart" button to play multiple rounds without closing the app.

Responsive, intuitive GUI with color-coded tiles.

🧱 Features
Gameplay: Players alternate turns, placing X or O. Illegal moves and repeated clicks are prevented.

Win/Tie Detection: Checks rows, columns, and diagonals; indicates winners in green or ties in orange.

Scoreboard: Displays cumulative scores for both players.

Reset Functionality: Restart rounds while preserving scores.

Clean, Minimal GUI: Java Swing interface built with JFrame, JPanels, JButtons, and JLabel.

🛠️ Getting Started
Prerequisites
Java 8 or higher.

Any Java IDE (Eclipse, IntelliJ, VSCode with Java support).

1.Installation & Launch
Clone the repository:
git clone https://github.com/yourusername/TicTacToeJava.git
cd TicTacToeJava

2.Compile the code:
javac TicTacToe.java
Run the game:
java TicTacToe
📂 Project Structure
TicTacToe/
├── src/
│   └── TicTacToe.java        # Main game logic & UI
├── .gitignore
└── README.md

🚦 How it Works
Game Initialization: Board tiles, score panel, info label, and restart button are created in the constructor.

Move Handling: Button clicks add X or O, check for winners/ties.

Game State: gameOver flag prevents extra input. Board gets disabled on round-over.

Score Management: Scores increment when someone wins and are reflected in the UI.

Restart Logic: The resetGame() method clears board state and resets turn while preserving scores.

✅ Example Flow
Launch the app.

X starts playing; O follows.

On a win (e.g., three Xs in a row), winning line highlights green, "X is the winner!" appears, X's score increases.

Click Restart to clear the board and start the next round.

Scores persist until you close the app.

👨‍💻 Contributing
Bug reports and improvements welcome!

Fork the repo, make changes, and open a pull request.

Please follow code conventions and Java naming practices.



