# Car Game

This is a simple car game implemented in C++. The game involves avoiding cars by moving left or right. The player controls a car at the bottom of the screen and must avoid collision with the cars coming from the top.

## Instructions
- Press 'a' to move the car to the left.
- Press 'd' to move the car to the right.
- Press 'escape' to exit the game.

## Prerequisites
- This code uses the `conio.h` library, which is specific to Windows systems.
- The code also uses the `windows.h` library for handling console input and output.

## How to Play
1. Select "Start Game" from the main menu.
2. Control the car using the 'a' and 'd' keys to move left or right, respectively.
3. Avoid collision with the cars coming from the top.
4. The game ends when a collision occurs.
5. The score is displayed on the screen, indicating the number of cars avoided.
6. Press any key to return to the main menu after the game ends.

## Functions

- `gotoxy(int x, int y)`: Moves the console cursor to the specified coordinates (x, y) on the screen.
- `setcursor(bool visible, DWORD size)`: Sets the visibility and size of the console cursor.
- `drawBorder()`: Draws the border of the game screen.
- `genEnemy(int ind)`: Generates the position of an enemy car at the specified index.
- `drawEnemy(int ind)`: Draws the enemy car at the specified index on the screen.
- `eraseEnemy(int ind)`: Erases the enemy car at the specified index from the screen.
- `resetEnemy(int ind)`: Resets the position of the enemy car at the specified index to the top of the screen.

...

