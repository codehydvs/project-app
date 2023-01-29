# project-app
practice 
#CSCI 6836: Assignment 4
Fairleigh Dickinson University Vancouver
Fall 2022
Assigned: Tuesday, November 15, 2022
Due: Beginning of class, Tuesday, November 22, 2022 using Webcampus
Instructions
This assignment has 100 points. Complete this assignment entirely on your own. Submission must follow
the guidelines stated in What to Submit and Quality Requirements exactly.
This assignment is about graph algorithms. You must implement your own graph data structure. Do not use any off-the-shelf graph libraries.
Problem Definition
Consider the following undirected graph.
Vertex 1 Vertex 2 Weight
A B 0.5
A C 0.75
A D 0.12
B E 0.7
B C 0.9
C D 0.45
C E 0.4
C F 0.3
D F 0.7
E F 0.2
E G 0.5
F G 0.2
Complete the following tasks.
1. Implement a graph data structure using adjacency list representation. Using this data structure, create
an instance of a graph object with the above edge weights (the graph must be undirected).
2. Implement the breadth first search (BFS) algorithm. Run BFS on the above graph with A as the start
node. Print the resulting BFS tree by outputting all the edges in it. Note that BFS does not use edge
weights.
3. Implement the depth first search (DFS) algorithm. Run DFS on the above graph with A as the starting
node. Print the resulting DFS tree. Note that DFS does not use edge weights.
1
What to Submit
Please submit the following files to Webcampus:
• All source code files. Change the file extension to .txt before uploading. Upload each source
code file separately. Do not upload a zip folder.
• A report (PDF document) that presents the outputs of the above algorithms on the given graph.
Quality Requirements
Programs must conform to the following:
• Programs must be written in Java, C#, Python, C++ or C.
• The implementations must be based on the algorithms as they are presented in Skiena’s textbook or
the CLRS textbook.
• Programs must be of high quality, check for error conditions and edge cases, and follow industry
standard coding and commenting guidelines for the chosen programming language.
• Code based on online resources such as tutorials or blogs or wikis will receive zero credit.
2