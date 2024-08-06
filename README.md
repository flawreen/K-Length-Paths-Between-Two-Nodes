# K-Length-Paths-Between_Two_Vertixes
Determine the number of K-Length paths between two vertixes in a directed graph using matrix multiplications in x86 Assembly.
## Prompts
1. file _0
    - 1 prints to STDOUT the adjacency matrix
    - 2 prints to STDOUT the number of K-Length paths between vertixes S and D with a statically allocated adjacency matrix
2. file _1
    - 3 prints to STDOUT the number of K-Length paths between vertixes S and D with a dynamically allocated adjacency matrix using mmap2

### STDIN for prompt 1
```
P                                         # prompt number (1 or 2)
N <= 100                                  # vertix number 
N lines: M(0), M(1), ..., M(N-1)          # each line represents the outdegree of each vertix
M(I) lines, I = 0, 1, ..., N-1            # on each line there is a neighbour of vertix I
```

### STDIN for prompts 2 and 3
```
P                                         # prompt number (1 or 2)
N <= 100                                  # vertix number 
N lines: M(0), M(1), ..., M(N-1)          # each line represents the outdegree of each vertix
M(I) lines, I = 0, 1, ..., N-1            # on each line there is a neighbour of vertix I
K                                         # path length
S                                         # source vertix
D                                         # destination vertix
```
