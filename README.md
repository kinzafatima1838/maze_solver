MAZE SOLVER USING RULE-BASED LOGIC
Overview
This project demonstrates a rule-based AI maze solver using Python and the Pygame library.
The maze is first generated randomly using logical rules, and then an AI agent solves it by following predefined movement rules (no learning involved).
The AI does not guess randomly. Instead, it:
⦁	Checks available paths (no walls)
⦁	Remembers visited cells
⦁	Backtracks when needed
⦁	Stops when it reaches the goal
⦁	This makes it a classic example of rule-based artificial intelligence.
Structure of the Program
The program starts by initializing Pygame, setting the window size, grid dimensions, clock, and basic display settings for the maze.
A Cell class is used to represent each block of the maze, storing its position, walls, and visited status, and drawing walls on the screen.
The maze generation function creates a random maze using a depth-first search approach by breaking walls between neighboring cells.
The solver function finds a path from the start cell to the end cell using stack-based logic and stores the solution path.
In the main loop, the maze is drawn continuously, the solution path is shown with red lines, and user events like closing the window are handled.
 
 
How to Run the Model
⦁	Download the Project
First, get the maze solver project on your system.
You can download the ZIP file or copy the project folder to any location on your computer.
⦁	Set Up the Environment
Make sure Python 3 is installed.
Install Pygame by running the following command in the terminal:
pip install pygame
This library is required to display the maze and the solution path.
⦁	Run the Simulation
Open the project folder and run the main Python file:
python main.py
A window will appear where the maze is generated automatically and the AI solver finds a path from start to end.

Output
⦁	A randomly generated maze displayed on the screen
⦁	Green lines representing maze walls
⦁	A red highlighted path showing the solution found by the AI
⦁	Real-time visualization of maze structure and final solution
 
Components in the Model
components      	Description
Cell	            Represents each block of the maze with walls and position
Maze Generator	  Creates the maze using rule-based logic and backtracking
Solver Agent    	Applies logical rules to move through open paths
Visualization	    Displays maze and solution using Pygame

Scenarios You Can Simulate
⦁	Different maze sizes (small or large grids)
⦁	Multiple possible paths with only one valid solution
⦁	Complex mazes with long backtracking paths
⦁	Faster or slower visualization of the solver’s movement

Reference
https://thepythoncode.com/article/build-a-maze-game-in-python
