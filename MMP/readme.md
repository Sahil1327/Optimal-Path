
# Functional Prototype - MMP

Functional prototype of the Minimum Marketable Product.


## Installation

Install pygame for python.

```bash
  pip install pygame
```
    
# About the program
The A* Pathfinding Visualization Web App showcases the A* pathfinding algorithm using Flask, a Python web framework. Upon accessing the app, users are presented with a grid table representing an environment. The grid contains cells indicating positions, with an orange dot as the starting point and a blue dot as the destination. Black boxes represent obstacles that block the path.

Users can interact with the grid by clicking on cells to toggle obstacles on or off. Clicking on an empty cell makes it an obstacle, and clicking on an obstacle cell removes it.

To initiate the A* pathfinding algorithm, users click the "Start Algorithm" button. The algorithm calculates the shortest path from the starting point to the destination, considering the obstacles and finding the most optimal route.

During the pathfinding process, the algorithm visualizes the progress on the grid, updating cells to show explored paths. It employs cardinal and diagonal movements to find the shortest path.

To quit the program, users can press the "Q" key to terminate the web app.

The functional prototype uses Flask for the backend, providing routes to update the grid, retrieve the current grid, and handle program termination. The frontend is built with HTML and JavaScript, utilizing jQuery for AJAX requests to communicate with the Flask backend. The grid visualization is dynamically generated and updated based on server responses.

By following this prototype, users can interact with the web app, observe the A* pathfinding algorithm in action, and witness the calculated shortest path from the starting point to the destination, considering obstacles in the environment.

Please note that the prototype focuses on the core functionality of the web app and grid visualization. The specific implementation of the A* algorithm is not provided, as it may vary depending on specific requirements and constraints.
![](https://github.com/nikhilkoche/Optimal-Path/edit/main/MMP/templ.png)
