# Global Path Planner with A* and Dijkstra
This repo focuses on path planning algorithms for finding optimal routes in a given map. It implements A* algorithm with two different heuristic functions, Dijkstra's algorithm, as well as three additional route optimal finding algorithms: brute force, nearest neighbour, and genetic algorithm.

## Introduction
Path planning is a fundamental problem in robotics, autonomous vehicle, and other areas when finding an optimal route from a start point to a goal point is essential. This repo explores various path planning algorithms and compare their performance in different scenarios.

## Algorithms Implemented
### A* Algorithm
A* is a popular pathfinding algorithm used to find the shortest path between two points in a graph. It uses a combination of the cost to reach a node and the estimated cost to the goal to determine which node to explore next.

#### Heuristic Functions
1. **Euclidean Distance**: This heuristic calculates the straight-line distance between the current node and the goal node.
![image](https://github.com/KAN201197/Global_Path_Planner/assets/128454220/1093be7f-3dda-4075-b06d-71678ecd146e)

3. **Manhattan Distance**: this heuristic calculates the distance between two points along the axis-aligned grid lines.
![image](https://github.com/KAN201197/Global_Path_Planner/assets/128454220/6bae5dd0-5479-4ea0-b4ac-fd22e64e9673)

### Dijkstra's Algorithm
Dijkstra's Algorithm is another pathfinding algorithm that finds the shortest paths from a single source node to all other nodes in a weighted graph. This algorithm does not use any heuristics function and explores nodes uniformly.
![image](https://github.com/KAN201197/Global_Path_Planner/assets/128454220/20b64684-5020-43bd-94be-c56cdbec9ca4)

### Route-Finding Algorithms
1. **Brute Force**: This algorithm search through all possible paths to find the optimal route.
2. **Nearest Neighbour**: This algorithm starts at a random node and repeatedly selects the nearest unvisited node until all nodes are visited, forming a tour.
3. **Genetic Algorithm**: This algorithm use a population of candidates solutions, apply genetic operators, and select the fittest individuals to evolve toward an optimal solution.

The result after applying Route-Finding Algorithms can be seen below.
![image](https://github.com/KAN201197/Global_Path_Planner/assets/128454220/5149ccbd-ef1f-4e72-b257-d59ccd6471bc)

