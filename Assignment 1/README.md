Dynamic Robot Movement Simulation This Jupyter Notebook demonstrates pathfinding algorithms, specifically A* and Uniform Cost Search (UCS), in a grid-based environment. Path planning is crucial for autonomous robots to navigate efficiently in various environments. This project implements two popular algorithms, UCS and A* Search, to find the optimal path for a robot to reach its goal while avoiding obstacles and conserving battery power.

Features UCS (Uniform Cost Search): This algorithm explores the grid space based on the cost of reaching each cell from the start position. It dynamically adjusts the path based on the accumulated cost, ensuring the robot moves optimally.

A Search:* A* Search enhances UCS by incorporating a heuristic function to guide the search towards the goal more efficiently. By combining the cost of reaching a cell with an estimate of the cost to reach the goal from that cell, A* Search finds the shortest path faster.

Battery Management: The robot has a limited battery that depletes as it moves through the grid. The project manages the battery level, triggering recharges when necessary to ensure the robot reaches its goal successfully.

Visualization: The project includes visualization capabilities to display the grid environment, the path taken by the robot, and the locations of obstacles, the start, and the goal. This visual representation aids in understanding the robot's movement and decision-making process.

Requirements Python 3.x NumPy Matplotlib Interpret Results:

The script will output the movements of the robot using UCS and A* algorithms, along with information such as recharge counts, total moves, and final battery percentage. Visualizations of the grid and the paths taken by the robot will be displayed. Usage Ensure you have Python and the required dependencies installed. Run the script Assignment-1.ipynb. The script will generate a random grid, find paths using A* and UCS algorithms, and visualize the results. The script will print the solution paths, the number of charge stations encountered, recharge counts, total moves, and final battery percentage. Files Assignment-1.ipynb: Main Python script containing the implementation of pathfinding algorithms, environment setup, and visualization. README.md: This file providing an overview of the script and instructions for usage.
