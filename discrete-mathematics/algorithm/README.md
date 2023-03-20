# What is algorithm
An algorithm is a set of well-defined instructions or a step-by-step procedure that is used to solve a problem or accomplish a specific task

## Dijkstra's algorithm
### Definiton
Given a weighted graph G, and a source vertex S the algorithm return the shortest path from S to each vertices.

### STEP
> 1. Pick start node and end node
> 2. Define start node as 0 and other(undefined) node as infinity
> 3. Pick a node which is shortest path from defined node. 
> 4. Update wight between defined node and undefined node
> 5. Repeat 2 ~ 4 until end node


## Prim’s algorithm
### Definiton
Prim’s algorithm is used to find the Minimum Spanning Tree for a given graph.

### STEP
> 1. Pick a node and connect it to its nearest node.
> 2. Examine the connected nodes and connect them to the nearest unconnected node.<br>
> *Note : chose smallest node which connected nodes*
> 3. Repeat step 2 until all nodes are connected.

## Kruskal’s algorithm
### Definiton
Kruskal’s algorithm is the concept that is introduced in the graph theory of discrete mathematics. It is used to discover the shortest path between two points in a connected weighted graph.


### STEP
> 1. start with the `cheapest` edges in the spanning tree ※that’s all.<br>
> 2. repeatedly add the cheapest edges that does not create cycle.<br>
> *Note : Should not create “**cycle”** because it should be tree.*