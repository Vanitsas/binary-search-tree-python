# Binary Search Tree (BST) Implementation

This repository contains a Python implementation of a Binary Search Tree, built as part of FreeCodeCamp's "Learn Tree Traversal by Building a Binary Search Tree" tutorial.

## Features
- Insert nodes into the BST
- Search for nodes
- Delete nodes
- Inorder traversal (sorted order)

## Usage
```python
from bst import BinarySearchTree

bst = BinarySearchTree()
nodes = [50, 30, 20, 40, 70, 60, 80]
for node in nodes:
    bst.insert(node)

print("Search for 80:", bst.search(80))
print("Inorder traversal:", bst.inorder_traversal())

bst.delete(40)
print("Inorder traversal after deleting 40:", bst.inorder_traversal())