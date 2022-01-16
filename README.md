
we are writing an algorithm to give birth to AI agent, we will teach it how to solve puzzles using hints. And just like humans we will try to teach AI to learn information from the given problem, how to make smart choices.


## Phase 1 [Completed]

### Requirements : 
1. There's a puzzle board of m rows and n columns
2. There's going to be say a bag of pieces in the form of list given to the AI
3. We are going to give no/some inteligent information to the AI

example :
As an input we are going to give a shuffled list of pieces 

list_pieces = [4, 5, 1, 2, 3, 8, 9 , 6, 7]

size of list_pieces = m * n

This is how it looks after putting it together

| 1 | 2 | 3 |

| 4 | 5 | 6 |

| 7 | 8 | 9 |....[3 x 3]


### Rules
1. Sorting algorithms are strictly not allowed for directly placing pieces together
2. [A1] : only piece around neighbours can be added
3. 


### Additional info / heuristic function : 
Like humans we are going to teach the AI how to find information from whatever is the input 
1. is given piece a corner piece, edge piece
    -> we usually start or identify a piece as corner piece or an edge piece which helps us identify if



### Algorithm
1. takes hint and learns how to solve puzzle using BFS and DFS separately
 

## Phase 2 [In pipeline]

### Goals -  
- Instead of a numeric puzzle, use actual pictorial puzzle. 
- using image processing and recognition find neighbouring puzzle pieces to complete the puzzle  
