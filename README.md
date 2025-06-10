# GAME-DEVELOPMENT-SNAKE-GAME

COMPANY NAME -CODTECH IT SOLUTIONS

NAME -AARYA DIPAK POUL

INTERN ID -CT08DK522

DOMAIN NAME -C++ PROGRAMMING

DURATION -8 WEEKS(APRIL 20th to JUNE 20th 2025)

MENTOR -NEELA SANTHOSH KUMAR



📍Overview


The classic Snake game is a foundational project in game development, ideal for beginners learning the fundamentals of graphics programming and logic-based game design. This project recreates the traditional Snake game using C++ and the SFML (Simple and Fast Multimedia Library). SFML provides an easy-to-use API for graphics, events, and timing, making it suitable for creating interactive 2D games.

In this Snake game, the player controls a snake that moves around the screen collecting fruit. Each time the snake eats a fruit, it grows longer. The challenge increases as the player avoids colliding with the snake's own body. The game has basic graphics using colored tiles and sprites to represent the snake and fruit on a grid-based layout.

🛠️How It Works


The game operates on a simple loop structure involving initialization, input handling, game logic updating, and rendering.

Initialization:

The game sets a 30x20 grid, with each tile being 16x16 pixels.

The snake starts with a default length and direction.

A fruit is placed randomly on the grid.

SFML loads textures (white.png for the grid and red.png for the snake and fruit).

Input Handling:

Player input is handled using keyboard events (Up, Down, Left, Right).

The direction of the snake is updated based on key presses, ensuring it doesn’t reverse into itself.

Game Logic (Tick Function):

Each frame, the snake’s body moves forward by copying the position of the previous segment.

Based on the current direction, the snake’s head moves accordingly.

If the head collides with the fruit, the snake grows, and a new fruit is placed randomly.

If the snake hits the edge of the screen, it wraps around to the opposite side.

Collision with the snake’s own body results in truncating the length up to the point of collision (as a penalty).

Rendering:

The screen is redrawn in each frame: background grid, snake, and fruit.

SFML sprites represent these elements for simple yet visually effective graphics.

Game Loop:

A clock manages timing between updates using a delay.

The game keeps running until the window is closed by the user.

📌Features


Grid-Based Movement: The game world is divided into a tile-based grid where all elements (snake and fruit) are aligned.

Wrap-Around Edges: When the snake hits the border, it reappears on the opposite side.

Self-Collision Detection: Prevents players from continuing after running into their own tail.

Simple Scoring Mechanic: The snake grows when fruit is consumed, which reflects player progress.

Keyboard Input Control: Smooth arrow key inputs allow real-time direction changes.

Randomized Fruit Placement: Keeps the gameplay dynamic by placing fruits at new locations each time.

📚Learning Objectives


This project is a great way to reinforce several core programming concepts:

SFML Library Usage:
Learn how to set up windows, handle sprites, events, and timing using SFML.

Basic Game Loop Architecture:
Understand how continuous game states are managed with input, update, and render phases.

Structs and Arrays:
Use of C++ structs to organize game entities (Snake segments, Fruit), and arrays for handling the snake’s body.

Collision Detection:
Learn basic techniques for detecting interactions between game elements.

Real-Time Input Handling:
Implement keyboard controls that modify game behavior in real time.

Random Number Generation:
Understand how to use the rand() function to place fruits unpredictably on the grid.

Game Timing:
Gain insight into frame timing and delay handling using SFML’s Clock.

Code Structuring:
Encourages clean separation between logic (e.g., Tick() function) and rendering, laying a foundation for larger game projects.


Output

![Image](https://github.com/user-attachments/assets/0b18846c-6202-4fa8-81e0-9740b0ae4bef)

