# AVL-Tree-Implementation
This project implements an AVL tree, a self-balancing binary search tree, in C++. The AVL tree ensures balance by maintaining the height difference between left and right subtrees to a maximum of 1 using left rotations and right rotations during insertion and deletion operations.

# Features
The AVL tree supports the following operations:

•	Insertion (insert): Adds a new element while maintaining balance using rotations.

•	Search (search): Checks if an element exists in the tree.

•	Deletion (deleteNode): Removes an element while keeping the tree balanced.

•	Balance Factor Calculation (bf): Determines the difference in height between left and right subtrees.

• Rotations: 

o	Left-Left (llrotation)

o	Right-Right (rrrotation)

o	Left-Right (lrrotation)

o	Right-Left (rlrotation)

•	Level Order Traversal (levelorder_newline): Displays the tree structure level by level.

# How It Works
1.	Insertion:

o	A new node is added following BST rules.

o	The tree checks balance factors and performs rotations if needed.

o	The height of nodes is updated accordingly.

2.	Deletion:

o	The node is removed similarly to BST deletion.

o	The in-order predecessor/successor replaces the deleted node.

o	The tree rebalances itself using appropriate rotations.
# Compilation & Execution
Requirements:

•	C++ Compiler (e.g., g++)
Compile the Code:
 g++ -o avl_tree avl_tree.cpp
Run the Program:
 ./avl_tree
Example Usage:
1. Display level order on newline
2. Insert
3. Delete
0. Exit
Choice: 2
Enter no.: 15
Choice: 2
Enter no.: 10
Choice: 2
Enter no.: 20
Choice: 1
15
10 20
File Structure
- avl_tree.cpp  # Main implementation
- README.md     # Project documentation
# Future Improvements

•	Implement search functionality.

•	Add a graphical representation of the tree.

•	Enhance efficiency with additional optimizations.

•	Improve user interface with better visualization of tree operations.
