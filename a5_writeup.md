# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. What are some things that you learned through this assignment? Think about the concepts of backtracking, constraint satisfaction, and search algorithms. Were there any particular challenges you faced while implementing the Board class methods or the DFS/BFS functions? How did you overcome them?

I learned that there are different methods for searching inside other variables. Both the DFS and BFS classes can be used tofind specific things in different ways. I had no major challenges trying to implement them, but I still have one question. Can both these classes give out the same output/answer no matter what which one one uses anytime?

2. How can you apply what you learned in this assignment to future programs or projects? Consider other types of problems that involve searching through possibilities, making decisions, and backtracking when those decisions don't work out. Can you think of real-world scenarios where DFS or BFS might be useful? What about other constraint satisfaction problems?

An example of applying BFS this in real life can be searching for open spots in a hotel room. First lookinh through the first floor, then the second, and so on until finding an open hotel.

DFS can be used in real life as looking for a specific toy. You can first try to look for it in a closet, then in a used materials box, and the toys box inside it, and if it can't find that toy then go look under the bed, and so on.

3. Explain how the Stack and Queue classes work and why they are important for DFS and BFS algorithms. Describe the difference between LIFO (Last In First Out) and FIFO (First In First Out) data structures. How does using a Stack versus a Queue change the way the search algorithm explores possible solutions? Why is one data structure better suited for depth-first search and the other for breadth-first search?

A stack class works like a stack of plates, people take from the top and add to the top as it is a hassle to add plates to the bottom.
A queue class is like a line at the store, one joins at the back and leaves at the front.
These two are different because of the ways they search for items in other variables. DFS searches deeply and then goes back, while BFS is like airport security as it looks into every person in a line waiting to get checked to be let in the airport.