# Bellman Ford Algorithm

Bellman Ford algorithm is used to find the shortest path in a weighted graph from a source vertex.

❗❗❗ Remember Bellman Ford algorithm works with negative weights.

# Steps :
1. Sort the given edges according to edge weights
2. If number of vertices are n, loop over edges n-1 times (Outer loop)
3. Loop over all the given edges(u,v) and relax the vertices if possible (check if dU + dUV < dV)
