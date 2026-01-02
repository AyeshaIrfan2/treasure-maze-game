🧭 Treasure Maze Game (C++)
📌 Introduction

The Treasure Maze Game is a console-based game developed in C++ that combines maze generation, player movement, scoring, and multiple difficulty levels. The objective of the game is to navigate through a randomly generated maze, collect treasures, avoid walls, and reach the exit before losing all lives.

This project demonstrates the use of data structures, recursion, dynamic memory allocation, control flow, and user interaction in C++. The game also uses UTF-8 characters and ANSI colors to enhance the visual experience in the console.

🎯 Game Objective

Navigate the player through the maze
Collect treasures to increase score
Avoid hitting walls (each hit reduces a life)
Reach the exit to complete the level
Finish all levels to win the game

🕹️ Game Features

Random Maze Generation using Depth First Search (DFS)
Multiple Difficulty Levels
Easy (1 Level, Small Maze)
Medium (2 Levels, Medium Maze)
Hard (3 Levels, Large Maze)

Treasure System

💰 Gold (+10 points)
🪙 Silver (+5 points)
💎 Diamond (+20 points)

Lives System

Player starts with 3 lives
Game ends when lives reach zero
Colorful & Emoji-Based UI
Score Tracking Across Levels
Replay Option

🎮 Controls
Key	Action
W	Move Up
S	Move Down
A	Move Left
D	Move Right
🧱 Symbols Used
Symbol	Meaning
🧍	Player
🟦	Wall
💰	Gold
🪙	Silver
💎	Diamond
🚪	Exit
🛠️ Technologies Used

Language: C++

Libraries:

<iostream>
<cstdlib>
<ctime>
<string>
<windows.h>

Concepts Applied:

Recursion (DFS Maze Generation)
Dynamic Memory Allocation
Arrays & Pointers
Conditional Statements
Loops
Random Number Generation
Console Handling (UTF-8 & Colors)

🚀 How to Run the Game

Compile the code using a C++ compiler (e.g., Visual Studio or g++)
Make sure the console supports UTF-8 characters
Run the program
Enter player name
Select difficulty level
Use W, A, S, D keys to play
