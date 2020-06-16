# Bipartite
Bipartite graph


Bipartite graphs are equivalent to two-colorable graphs i.e., coloring of the vertices using two colors in such a way that vertices of the same color are never adjacent along an edge.


If Adjacency matrix is used, then:

Worst time complexity case: O(V^2)
Average time complexity case: O(V^2)
Best time complexity case: O(V^2)
Space complexity: O(V^2)

where V is the number of vertices.

In this algorithm, each vertex of the graph needs to be traversed once, and each neighbour of a vertex is traversed once. Since we are using an adjacency matrix, this results in a complexity of O(V^2).


Applications of bipartite graphs:
1. Bipartite graph can be used in the medical field in the detection of lung cancer, throat cancer etc.

2. Used in search advertising and e-commerce for similarity ranking.

3. Predict movie preferences of a person.

4. Stable marriage and other matching problems.
