Reguirements - pygame 

The project visualizes how A* search algorithm finds the shortest path from starting location to target location. 

A* search algorithm - f(n) = g(n) + h(n)

g(n) is the distance from start to n location and h(n) is the distance from n location to target location. h(n) is estimated in this implementation with manhattan distance.

At the beginning, distance from start location's neighbors to target location is estimated with A* search algorithm. The neighboring location where f(n) is the smallest is selected and then f(n) is calculated for its neigbors. This is repeated until the target location is reached.

The code file has comments to help to understand it.

