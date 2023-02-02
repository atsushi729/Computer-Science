# Graph
## What is graph
Graph is a discrete structure which consist of node(vertices) and edges connecting them.

### Definition of Vertex
vertex is basic element of a graph and which can be drawn as node or dot.<br>
Set of vertices of G is usually denoted by V(G) or V

`V(G) = {v1, v2, v3}`


### Definition of Edges
It is a like between 2 vertices, and it can be drawn as a line connection two vertices.<br>
The set of edges in a graph G is usually denoted by E(G) or E.<br>

`E(G) = {e1, e2} = {{v1, v2}, {v2, v3}}`


### Walk
A walk can be defined as a sequence of vertices and edges of graph which can be repeated edges and vertices.<br>
So for a walk, the following two points are important, which are described as follows:<br>

> Points :
> * Edges can be repeated
> * Vertex can be repeated

#### Open and Closed walk
If started vertices and end vertices are same, then we call closed vertices. On the other hand, if start and end vertices are different, it is call as open walk
* Closed walk = `A, B, C, D, E, C, A`  
* Open walk = `A, B, C, D, E, C`


### Trail
A trail can be described as ***open walk*** which where no edge is allowed to repeat. In the trails, the vertex can be repeated.
So for a trail, the following point is important, which is described as follows:

> Points :
> * Vertex can be repeated

### Circuit
A circuit can be defined as a ***closed walk*** where no edge is allowed to repeat.
So for a circuit, the following two points are important, which are described as follows:
> Points : 
> * Edges cannot be repeated
> * Vertex can be repeated

### Cycle

### Hamilton Path