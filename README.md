# Pacman 4

Pacman 4 is a desktop game inspired by the classic Pac-Man, developed in Java.

## Project Structure
- `Main.java` → Main entry point.
- `GameController.java` → Game logic and control.
- `GameView.java` → Game interface.
- `BoardCellRenderer.java` & `BoardTableModel.java` → Board rendering and data model.
- `HighScores.java` & `HighScoresView.java` → High scores management.
- `UpgradeSpawnerThread.java` → In-game upgrade spawning.
- `resources/` → Images, sounds, and other assets.

## How to Run
1. Make sure **Java JDK 8+** is installed on your machine.
2. Open a terminal and navigate to the project folder.
3. Compile:
   ```bash
   javac *.java
