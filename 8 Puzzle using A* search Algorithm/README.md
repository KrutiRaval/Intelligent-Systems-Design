# 8 Puzzle using A* Search Algorithm 

A* search algorithm is mainly used for path finding and path traversal in solving problems by searching. It plays an important role in Informed Search Strategies.It solves the limitations of the greedy algorithm by considering the best heuristic function as well as considering the uniform cost value. The main aim here is to avoid expanding paths that are already expensive. This search algorithm is thus Optimal.

8 Puzzle Problem: A 3×3 board with 8 tiles is given where every tile has one number from 1 to 8 and one empty space with number 0 in our case. The objective is to place the numbers on tiles to match final configuration using the empty space. We can slide four adjacent (left, right, above and below) tiles into the empty space.

Evaluation function: f(n) = g(n) + h(n)

g(n) = cost so far to reach node

h(n) = estimated cost to goal from node

f(n) = estimated total cost of path through node to goal

A∗ search uses an admissible heuristic

i.e., h(n) ≤ h∗(n)
where h∗(n) is the true cost from n.

A∗ search expands lowest g + h
