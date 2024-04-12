[Back to Portfolio](./)

Dijkstra's Shortest Path with Adjcentcy matrix
===============

-   **Class:** Data Structures
-   **Grade:** (A/100)
-   **Language(s):** C++
-   **Source Code Repository:** [ATM2100/Dijkstra](https://github.com/ATM2100/Dijkstra)  
    (Please [email me](mailto:atmacklin@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

Implements a Graph and Dijkstra's shortest path. 

## How to compile and run the program

How to compile (if applicable) and run the project.

```
make
```
This will both compile and run the project (see Fig. 1).

![screenshot](/images/project2/Fig1.png)  
Fig 1. Dijkstra's Shortest path having run.

## How to make changes and test the file
You can test this program by editing main.cpp, and then running make. The functions to consider and when are as follows:

graph.addEdge(start, end, weight)

Will add more edges to the graph, and thus more edges dijkstra's will have to consider.

graph.removeEdge(start, end)

Removes an edge.

graph.print()

prints the graph to the cli.

graph.dijkstraShortestPath(start, end)

finds the shortest path from "start" to "end".

[Back to Portfolio](./)