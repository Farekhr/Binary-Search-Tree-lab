# Binary-Search-Tree-lab
COMPENG 2SI3 Binary Search Tree Lab

Here, I delved deep into binary search tree implementations, learning how to work with this abstract data type. This code was used as an add-on to an existing snake game implementation to improve efficiency and run-time. This code was deeply analyzed to ensure time and space complexity optimization.

- Implement a Binary Search Tree (BST) that sorts `objPos` objects by their ASCII prefix character field, aiming to display collected treasures in alphabetical order without explicit sorting.
- Key Operations:
  - Constructor/Destructor: Initialize and properly clean up the tree, ensuring all nodes are deleted.
  - Insertion: Add `objPos` objects to the BST, automatically sorting them by the prefix field. If an object with the same prefix exists, add the new object's number to the existing one's number field.
  - Deletion: Remove nodes with matching `objPos` prefix fields, handling all cases of node removal (leaf, one child, two children).
  - Search: Check if a specific `objPos` object (by prefix) exists in the tree and whether any node's number field exceeds a given threshold (`WIN_SPECIAL_THRES`), which determines the game's winning condition.
  - Traversal: Implement inorder traversal to print all nodes in sorted order and support other operations like finding the minimum or checking for leaf nodes.
- Objective: Support a Treasure Hunter game mode where collecting treasures with the same prefix sums their numbers, and winning conditions are evaluated based on these sums. 

This task requires detailed understanding and application of BST principles, focusing on sorting, searching, and dynamic data handling within the context of a competitive game.
