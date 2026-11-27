Maze Game

Custom feature: Visibility radius
The player can see their current tile and the tiles directly above, below, left,
and right. All other tiles are hidden in black. The visible area moves with the
player and does not remember previously explored tiles.

How to test:
1. From the project folder, compile the Java files:
   javac -d out *.java
2. Run the game:
   java -cp out MazeGUI
3. Choose Game > Open and select level1.csv, level2.csv, or level3.csv.
4. Move with the arrow keys. Confirm only the player and the four adjacent
   directions are visible, and that the visible area follows the player.
