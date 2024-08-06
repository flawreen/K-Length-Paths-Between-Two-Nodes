# K-Length-Paths-Between-Two-Nodes
Determine the number of K-Length paths between two nodes in a directed graph using matrix multiplications in x86 Assembly.
## Prompts
1. file _0
    - [1] prints to STDOUT the adjacency matrix
    - [2] prints to STDOUT the number of K-Length paths between nodes S and D with a statically allocated adjacency matrix
2. file _1
    - [3] prints to STDOUT the number of K-Length paths between nodes S and D with a dynamically allocated adjacency matrix using mmap2

### STDIN for prompt 1
```
P                                         # prompt number (1 or 2)
N <= 100                                  # node number 
N lines: M(0), M(1), ..., M(N-1)          # each line represents the outdegree of each node
M(I) lines, I = 0, 1, ..., N-1            # on each line there is a neighbour of node I
```

### STDIN for prompts 2 and 3
```
P                                         # prompt number (1 or 2)
N <= 100                                  # nodes number 
N lines: M(0), M(1), ..., M(N-1)          # each line represents the outdegree of each nodes
M(I) lines, I = 0, 1, ..., N-1            # on each line there is a neighbour of nodes I
K                                         # path length
S                                         # source nodes
D                                         # destination nodes
```
