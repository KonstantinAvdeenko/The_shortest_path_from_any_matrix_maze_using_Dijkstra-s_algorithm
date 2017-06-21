This program in the C# programming language produces the shortest path from the matrix maze,
built by the user, using Edsger Dijkstra's algorithm for constructing a minimum spanning tree.
The construction of a matrix maze is possible for matrices of any dimensions, which the user enters.
To build a matrix maze, the user enters each element of the matrix, separated by a space or a value
"0" - indicating the passage in the maze, or the value "-1" - denoting a wall between the passages.
Before finding the shortest path from the matrix maze - the user enters the coordinates of the beginning of the path and exit coordinates.
If the path to the exit coordinate is not possible due to the absence of passes in the maze, the user is notified that
that there is no way. After finding the shortest path from the matrix maze, the user is shown how much and
what coordinates of the path you need to go.

The main module VihodIzLabirintaKrathaishiiPutAlgDeikstra contains a single main function:
Main - fully performing the above task.