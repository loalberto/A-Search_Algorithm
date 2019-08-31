# A-Search_Algorithm

This algorithm was designed to find the shortest path in a graph. It uses an A* implementation in which, it calculates its
heuristics using the euclidean distance and then stores every neighbor in a frontier. It then stores an 'f' value, that is computed
by adding the cost of getting to this vertex and the heuristic value. The way for it to decide which vertex to traverse next, it
uses a greedy approach on the frontier, in which it chooses the next vertex by finding the vertex with the smallest 'f' value.
It keeps doing this until the fontier is empty or the chosen vertex is the goal vertex. In order to trace the path, I added a
linked list implementation, in which the start node is the head and the goal node is the tail, so that it can traverse from the 
goal node back to the start node so that it can return the vertices that it passed to get there.
