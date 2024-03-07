
Dynamic Robot Movement Simulation is a Jupyter Notebook illustrating pathfinding algorithms, particularly A* and Uniform Cost Search (UCS), within a grid-based setting. Path planning is essential for autonomous robots to efficiently navigate diverse environments. This project presents two well-known algorithms, UCS and A* Search, to determine the optimal path for a robot to reach its destination while evading obstacles and conserving battery power.

Key Features:

UCS (Uniform Cost Search): This algorithm traverses the grid space based on the cost associated with reaching each cell from the starting point. It dynamically adjusts the path considering the accumulated cost, ensuring the robot moves optimally.

A* Search: A* Search enhances UCS by incorporating a heuristic function to guide the search more efficiently towards the goal. Combining the cost of reaching a cell with an estimate of the cost to reach the goal from that cell, A* Search discovers the shortest path faster.

Battery Management: The robot possesses a finite battery that diminishes as it traverses the grid. The project manages the battery level, initiating recharges when necessary to ensure the robot successfully reaches its goal.

Visualization: Visualization capabilities are included to showcase the grid environment, the robot's path, and the locations of obstacles, the starting point, and the goal. This visual representation aids in comprehending the robot's movement and decision-making process.

Requirements:

Ensure Python 3.x, NumPy, and Matplotlib are installed.

Interpreting Results:

Upon running the script, the robot's movements using UCS and A* algorithms will be displayed, along with details such as recharge counts, total moves, and final battery percentage. Visualizations of the grid and the paths taken by the robot will also be presented.

Usage:

Install Python and the necessary dependencies.
Run the script Assignment-1.ipynb.
The script will generate a random grid, determine paths using A* and UCS algorithms, and visualize the outcomes.
Solution paths, encountered charge stations, recharge counts, total moves, and final battery percentage will be printed.
Files:

Assignment-1.ipynb: Primary Python script containing the implementation of pathfinding algorithms, environment setup, and visualization.
README.md: This file provides an overview of the script and instructions for usage.
