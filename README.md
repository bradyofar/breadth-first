# breadth-first
Implementing BFS in Java

/* 
Breadth-first search can be a useful algorithm, particularly when the step costs are all equal or you care about the path length and not the path cost. This activity is in two parts:
Implement breadth-first search yourself for a small example problem;
Share and discuss your implementation with other students in a small group, then improve your own implementation (if necessary) using the best ideas from the group. 
This activity will help to reinforce your knowledge of uninformed search strategies, and help to prepare you for the exam. 

Implement the graph search version of breadth-first search (as described in AIMA Chapter 3 Section 3.4.1) in Java to solve the small problem described below. The implementation does not need to be a generic breadth-first search, it can be specific to this problem. In particular, a state may be represented with a single integer, and the expansion of a node can be implemented with a simple look-up table, indexed by an integer s and containing a list of integers (representing the states adjacent to s).

Your implementation of the frontier does not need to be the most efficient choice. You do not need to extract the solution at the end - just verifying that you have reached a goal state is enough. Finally, there is no need to store the names of the actions. It should be possible to implement your program with just one Java class.

The problem scenario is the vacuum world that you saw in Lesson 1. The diagram of all 8 states is shown below. Each state has a number in red. You will need to represent the states and transitions shown in the diagram in your program in some form. For example, state 1 expands to states 1, 2 and 3 (by the actions Left, Right and Suck).
*/
