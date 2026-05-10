 Assignment 4: Graph Traversal and Representation System

 Project Overview

This project demonstrates graph traversal algorithms using Java.

The graph is implemented using an adjacency list representation.
Each graph contains vertices and edges.

Traversal algorithms implemented:
Breadth-First Search (BFS)
 Depth-First Search (DFS)

The project also measures traversal performance on graphs of different sizes.


 Graph Structure

A graph consists of:
 Vertices (nodes)
 Edges (connections)

This project uses an undirected graph.

Example:
0 -> 1 -> 2

 Class Descriptions

 Vertex Class

Represents a graph vertex.

Fields:
 id

Methods:
- Constructor
- Getter
- toString()

---

Edge Class

Represents a connection between two vertices.

Fields:
- source
- destination

Methods:
- Constructor
- Getters
- toString()



Graph Class

Stores graph data using an adjacency list.

Main methods:
- addVertex()
- addEdge()
- printGraph()
- bfs()
- dfs()



Experiment Class

Runs graph traversal experiments and measures execution time.

Methods:
- runTraversals()
- runMultipleTests()
- printResults()

---

BFS Algorithm

Breadth-First Search visits nodes level by level.

Steps:
1. Start from a vertex
2. Add it to queue
3. Visit neighbors
4. Continue until queue becomes empty

Use cases:
- Shortest path
- Social networks
- Web crawling

Time Complexity:
O(V + E)
DFS Algorithm

Depth-First Search explores as deep as possible before backtracking.

Steps:
1. Start from a vertex
2. Visit neighbor recursively
3. Continue deeper
4. Backtrack when needed

Use cases:
 Path finding
 Cycle detection
 Topological sorting

Time Complexity:
O(V + E)

Analysis Questions

How does graph size affect BFS and DFS performance?

As graph size increases, traversal time also increases because more vertices and edges must be visited.

Which traversal is faster?

Both algorithms showed similar performance because both have O(V + E) complexity.

Do results match expected complexity?

Yes. The execution time increased proportionally with graph size.

How does graph structure affect traversal order?

Different edge connections change the visiting order of vertices.

 When is BFS preferred over DFS?

BFS is preferred when finding the shortest path.

 What are the limitations of DFS?

DFS may use more recursion depth and may not find the shortest path.



Reflection

This assignment helped me understand graph traversal algorithms and adjacency list representation.

I learned how BFS uses queues and DFS uses recursion. I also learned how graph size affects performance.

One challenge was implementing traversal correctly while avoiding revisiting nodes.


