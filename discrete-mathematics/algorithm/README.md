# What is algorithm


## Dijkstra's algorithm
### Definiton
Given a weighted graph G, and a source vertex S the algorithm return the shortest path from S to each vertices.

### STEP

---

1. Pick start node and end node
2. Define start node as 0 and other(undefined) node as infinity
3. Pick a node which is shortest path from defined node. 
4. Update wight between defined node and undefined node
5. Repeat 2 ~ 4 until end node


## Prim’s algorithm
### Definiton
Prim’s algorithm is used to find the Minimum Spanning Tree for a given graph.

### STEP

---

**Prim’s algorithm:
1. Pick a node and connect it to its nearest node.
2. Examine the connected nodes and connect them to the nearest unconnected node.
*Note : chose smallest node which connected nodes*
3. Repeat step 2 until all nodes are connected.**

## Kruskal’s algorithm
### Definiton
