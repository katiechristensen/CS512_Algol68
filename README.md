# CSCI 512 - Design and Implementation of Computer Programming Languages
## Winter 2023
### Algol 68 Translation of a C Implementation of the Floyd-Warshall Algorithm

Katie Christensen


The Floyd-Warshall algorithm finds the shortest paths between all pairs of vertices in a weighted graph
with positive or negative edge weights.

The C program reads a file describing the graph and prints out for each vertex pair the shortest distance and a path with
that distance. The input file has the following form: The first line of the file specifies the number of
vertices and edges. This is followed by a line for each edge giving the source and destination vertices
for the edge and the weight for that edge. The output of the program shows the pair distance and path. Note that the edges are listed in ascending order. A “translation” of this program is written in Algol 68. 