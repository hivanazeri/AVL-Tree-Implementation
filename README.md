# AVL-Tree-Implementation
This project implements an AVL tree, a self-balancing binary search tree, in C++. The AVL tree ensures balance by maintaining the height difference between left and right subtrees to a maximum of 1 using left rotations and right rotations during insertion and deletion operations.
The AVL tree supports the following operations:

Insertion (insert): Adds a new element while maintaining balance using rotations.

Search (search): Checks if an element exists in the tree.

Deletion (deleteNode): Removes an element while keeping the tree balanced.

Balance Factor Calculation (bf): Determines the difference in height between left and right subtrees.

Rotations:

Left-Left (llrotation)
Right-Right (rrrotation)
Left-Right (lrrotation)
Right-Left (rlrotation)

Level Order Traversal (levelorder_newline): Displays the tree structure level by level.

How It Works

Insertion:
A new node is added following BST rules.
The tree checks balance factors and performs rotations if needed.
The height of nodes is updated accordingly.

Deletion:

The node is removed similarly to BST deletion.
The in-order predecessor/successor replaces the deleted node.
The tree rebalances itself using appropriate rotations.
Compilation & Execution

Requirements:
C++ Compiler
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


