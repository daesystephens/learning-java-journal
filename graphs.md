# GRAPH
<!-- Reference: https://medium.com/basecs/from-theory-to-practice-representing-graphs-cfd782c5be38 -->

There are two fundamental ways we implement a graph

1. Adjacency Matrix
2. Adjacency List

## Adjacency Matrix
Is a matrix that represents exactly which **vertices/nodes** in a graph have edges between them. </br>
The matrix serves as a lookup table, where a value of ```1``` represents an edge that exists, and ```0``` represents an edge that does not.
![matrix](../learning-java-journal/assets/matrix.jpeg)

## Adjacency List: the hybrid choice
An adjacency list **is an array of linked lists** that serves the purpose of representing a graph, but also makes it easy to see which other vertices are adjacent to other vertices.</br>
Each vertex in a graph can easily reference its neighbors through a **linked list**.
![list](../learning-java-journal/assets/list.jpeg)
