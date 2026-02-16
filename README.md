# Retro Snake

A C++ Snake game built with the raylib library, emphasizing clean Object-Oriented Programming (OOP) principles.

---

## Features

* **Audio Feedback:** Integrated sound effects for eating food and "game over" (kill) events.
* **Win Detection:** Logical checks to determine when the player has successfully filled the grid.
* **Clean OOP Design:** Encapsulated logic for Snake, Food, and Game state management.
* **Grid-Based Movement:** Classic arcade-style precision and responsiveness.

---

## Controls

Navigate the snake using the arrow keys:

| Action | Key Binding |
| :--- | :--- |
| **Move Up** | Up Arrow |
| **Move Down** | Down Arrow |
| **Move Left** | Left Arrow |
| **Move Right** | Right Arrow |

---

## Technical Overview

The project is structured into distinct classes to ensure a modular codebase:

* **Snake Class:** Manages the body segments, movement direction, and growth logic.
* **Food Class:** Handles randomized spawning within the grid boundaries.
* **Game Class:** Acts as the main controller, handling collision detection, scoring, and the game loop.

---

## Prerequisites

To build and run this project, you will need:
* A C++ compiler (GCC, Clang, or MSVC)
* [raylib](https://www.raylib.com/) installed and configured on your system

---

## Credits 

* **Library:** [Raylib](https://www.raylib.com/)

---

## License

This project is open-source. Feel free to use and modify it as you see fit.