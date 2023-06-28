
# Functional Prototype - MVP

Functional prototype of the Minimum Viable Product.


## Installation

Install pygame for python.

```bash
  pip install pygame
```
    
# About the program
The A* Pathfinding Visualization Web App is designed to demonstrate the A* pathfinding algorithm using Flask, a Python web framework. The web app allows users to visualize the pathfinding process on a grid-based environment.

Upon accessing the web app, users are presented with a grid table representing the environment. The grid consists of cells where each cell represents a position in the environment. The starting point is indicated by an orange dot, and the destination point is indicated by a blue dot. Additionally, black boxes represent obstacles that obstruct the path.

Users can interact with the grid by clicking on cells to toggle obstacles on or off. Clicking on an empty cell turns it into an obstacle (black box), and clicking on an obstacle cell removes the obstacle.

To initiate the A* pathfinding algorithm, users can click the "Start Algorithm" button. The algorithm will calculate the shortest path from the starting point to the destination point, considering the obstacles and finding the most optimal route.

Throughout the pathfinding process, the algorithm will visualize the progress on the grid table, updating the cells to indicate the explored paths. The algorithm will use a combination of movement in cardinal directions (up, down, left, and right) and diagonal directions (top-left, top-right, bottom-left, and bottom-right) to find the shortest path.

To quit the program, users can press the "Q" key, which triggers the termination of the web app.

The functional prototype is implemented using Flask as the web framework. The Flask app includes routes to update the grid, retrieve the current grid, and handle the termination of the program. The frontend is built using HTML and JavaScript, leveraging jQuery for AJAX requests to communicate with the Flask backend. The grid visualization is dynamically generated and updated based on the server's response.

By following the provided prototype, users can interact with the web app, visualize the A* pathfinding algorithm in action, and observe the calculated shortest path from the starting point to the destination point, considering obstacles within the environment.

It's important to note that the prototype focuses on the basic functionality of the web app and the grid visualization. The implementation of the A* algorithm itself is not included in the prototype, as it may vary depending on specific requirements and constraints.

Overall, the A* Pathfinding Visualization Web App provides a foundational framework for building a more comprehensive and interactive tool for understanding and experimenting with the A* pathfinding algorithm in a web-based environment.
![](https://github.com/nikhilkoche/Optimal-Path/blob/main/MVP/2023-06-28%2012-26-53.gif)
