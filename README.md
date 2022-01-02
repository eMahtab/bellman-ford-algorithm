# Bellman Ford Algorithm

Bellman Ford algorithm is used to find the shortest path in a weighted graph from a source vertex.

❗❗❗ Remember Bellman Ford algorithm works with negative weights.

## Algorithm :
1. Take a `distances[]` array and fill it with `Integer.MAX_VALUE` , set `distances[startingVertex] = 0`
2. Sort the given edges according to edge weights
3. If number of vertices are n, loop over edges **n-1** times (Outer loop)
4. Loop over all the given edges(u,v) and relax (check if `dU + dUV < dV`) the vertices if possible (Inner loop)
