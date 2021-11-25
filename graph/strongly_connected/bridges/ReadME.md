Brute force

To get critical connections:
For all edges:
1. Remove an edge
2. check if it breaks the graph
3. add it back

Time complexity:
E times, we perform:
remove edge -> cont time
connComponents: O(V+E)
add back -> const time

Time COmplexity = E*O(V+E)
