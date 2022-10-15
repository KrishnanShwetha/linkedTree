# linkedTree

This project invole implementing a simple java program for a linked Tree. A linked Tree is a data structure that consists of a set of data records(nodes) linked together and organized by references(links or pointers).

This program consists of :

The LinkedTree class - a class that represents a binary tree containing data items with integer keys. If the nodes are inserted using the insert method, the result will be a binary search tree.

- preorderPrintTree: Recursively performs a preorder traversal of the tree/subtree whose root is specified, printing the keys of the visited nodes. Note that the parameter is *not* necessarily the root of the entire tree. 
- inorderPrintTree: Recursively performs an inorder traversal of the tree/subtreewhose root is specified, printing the keys of the visited nodes. Note that the parameter is *not* necessarily the root of the entire tree. 
- NodePlusDepth: Inner class for temporarily associating a node's depthwith the node, so that levelOrderPrint can print the levels of the tree on separate lines.
- levelOrderPrint: Prints the keys of the tree in the order given by a level-order traversal.
- search: Searches for the specified key in the tree. If it finds it, it returns the list of data items associated with the key. Invokes the recursive searchTree method to perform the actual search.
- searchTree: Recursively searches for the specified key in the tree/subtreewhose root is specified. Note that the parameter is not necessarily the root of the entire tree.
- insert: Inserts the specified (key, data) pair in the tree so that the tree remains a binary search tree.
- newNode: Inserts a new node
- insertKeys: inserts a key
- delete: Deletes the node containing the (key, data) pair with the specified key from the tree and return the associated data item.
- deleteNode: Deletes the node specified by the parameter toDelete.  Parent specifies the parent of the node to be deleted. 
- pre-order and post-order iterators 
