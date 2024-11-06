# Graph Representation

Graphs are widely used structures in computer science, representing entities and their connections. They are made up of **vertices (or nodes)** and **edges (or connections)**. To store and manipulate graphs, two popular methods are commonly used: the **adjacency matrix** and the **adjacency list**.

## 1. Adjacency Matrix

An adjacency matrix is a 2D array used to represent a graph. Each cell `(i, j)` in the matrix holds a value (typically `1` or `0` in an unweighted graph) to indicate whether there is an edge between vertex `i` and vertex `j`. This representation is especially useful for dense graphs, where most nodes are connected.

- **Time Complexity** for edge existence check: \(O(1)\)
- **Space Complexity**: \(O(V^2)\), where `V` is the number of vertices.
