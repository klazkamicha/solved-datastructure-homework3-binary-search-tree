Download Link: https://assignmentchef.com/product/solved-datastructure-homework3-binary-search-tree
<br>
<h1>Binary Search Tree</h1>

You are to code a binary search tree. A binary search tree is a collection of nodes, each having a data item and a reference pointing to the left and right child nodes. The left child node and all of its children are less than the data. The right child node and all of its children are greater than the data. Therefore, all elements added to the tree must implement Java’s generic Comparable interface.

All methods in the BST that are not <em>O</em>(1) <strong>must be implemented recursively</strong>, except for level order traversal.

It will have two constructors: the no-argument constructor (which should initialize an empty tree), and a constructor that takes in data to be added to the tree, and initializes the tree with this data. You shouldn’t need to do anything for the no-arg constructor for it to work. Any attempts to add data that is already in the tree should be ignored (the tree shouldn’t be changed, and the duplicate item shouldn’t get added).

<strong>Nodes</strong>

The binary search tree consists of nodes. The BSTNode class will be given to you; do not modify it.

<h2>Methods</h2>

You will implement all standard methods for a Java data structure (add, remove, etc.). See the javadocs for details. Note that some methods are worth more than others. If add is incorrect, then you are likely to fail most tests, as adding is crucial to the usability of a data structure.

<h2>Traversals</h2>

You will implement 4 different ways of traversing a tree: pre-order traversal, in-order traversal, postorder traversal, and level-order traversal. The first 3 MUST be implemented recursively; level-order is best implemented iteratively. You may import Java’s LinkedList/ArrayList classes as appropriate for these methods (but they may only be used for these methods). For a level-order traversal, you may use Java’s Queue interface.

<h2>Height</h2>

You will implement a method to calculate the height of the tree. The height of any given node is max(left.height, right.height) + 1. A leaf node has a height of 0, while the height of an empty tree is -1.