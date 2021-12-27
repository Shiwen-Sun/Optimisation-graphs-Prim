# Optimisation-graphs-Prim


The main objective of this session is to implement Prim’s algorithm to compute Minimum Spanning Trees. The lab
is language agnostic, i.e., you can choose whatever programming language you prefer to implement it.
Prim’s algorithm is a greedy algorithm: it solves the problem by locally optimal choices at each stage.


Steps
1. define our own data structures to represent nodes and set of nodes, as set of nodes are needed in the algorithm.
We use the networkx Python library.

2. implement Prim’s algorithm and test it on the example presented during lecture.

3. test our implementation of Prim’s algorithm on the problem contained in the edges.txt file.
The first line in edges.txt gives us the number of vertices and the number of edges in the graph. Each
following line represents an edge with the source vertex, the destination vertex and the cost of the edge. A
Python script reader_students.py is available to help you understand how to extract the vertices from the
files.
The sum of the cost of the edges in the MST should be -3612829.

4. (advanced) write a better implementation of Prim’s algorithm using a binary heap. We reuse Python
standard implementation of a heap. Read the documentation to understand how to deal with updates of nodes.
Verify that execution time is better than the naive implementation.
