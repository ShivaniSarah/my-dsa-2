# my-dsa-2

This repo is for Hard problems.

Time complexity (TC) & Space Complexity(SC) Analysis

In dfs or bfs TC = O(n) or O(V+E) => mot problems cover graph and binary tree or bonary search tree

SC => recursion stack => O(height) , in balanced tree it SC = O(log n) and skewed tree it is SC = O(n) in case of dfs

SC => recursion stack => O(max width of last level) => 2^(level-1) => O(n) or O(V) which is the queue size maximum worst case , in case of bfs => The worst-case space complexity could still be O(V) if the graph is a complete graph, and all nodes end up in the queue at once,
 a complete binary tree where the width of the last level is close to V/2

In short , we can assume space complexity of dfs or bfs as O(V)

In Union Find => TC= O( V²*  α(V) ) ≈ O(V²) where α(V) is inverse ackermann function which grows slowly and is very small

In Union Find => SC => O(V)

In recursion , is 2^(n-1) where n is the no of levels.
