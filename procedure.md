# Procedure
Breadth first search explores the space level by level only when there are no more states to be explored at a given level does the algorithm move on to the next level.
We implement BFS using lists open and closed to keep track of progress through the state space. In the order list, the elements will be those who have been generated but whose children have not been examined. The closed list records the states that have been examined and whose children have been generated. The order of removing the states from the open list will be the order of searching. The open is maintained as a queue on the first in first out data structure. States are added to the right of the list and removed from the left
The objective is to determine route utilizing the BFS with open and closed List, which are contingent upon the input provided by the user.

## Create the Graph and set the search parameters:
    Select creating graph manual/random
    Enter Source Node and Destination Node
    Initiate Search on Graph
## Generate solution:
    Visualize the steps 
    Visualize the path from selecting a starting point on the graph and then following a the BFS algorithm with open and closed list
    Iterations can be animated; paths can be highlighted.
    The result will be a path which displays the end of the search.

## Evaluate :
    Define following:	
    Path and algorithm iterations
