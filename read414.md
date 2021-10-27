# Trees

 - Node 

  a component contain it’s own values, and references to other nodes
- Root 

 Node at the beginning of the tree

- K 

 A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.

- Left 
 A reference to one child node in a binary tree

- Right 

A reference to the other child node, in a binary tree
- Edge 

 The edge in a tree is the link between a parent and child node
- Leaf 

 A leaf is a node that does not have any children
- Height - The height of a tree is the number of edges from the root to the furthest leaf


![](https://camo.githubusercontent.com/259378cb7a863637fcce827d8c85618ed189140b33b2656e36986f0e75b6859c/68747470733a2f2f6d796d7573696e672e636f2f77702d636f6e74656e742f75706c6f6164732f323031372f31302f547265652d5465726d2d333030783137302e676966)


# Traversals

There are two categories of traversals when it comes to trees:

### Depth First

methods for depth first traversal:

- Pre-order: root >> left >> right
- In-order: left >> root >> right
- Post-order: left >> right >> root

## Breadth First

Breadth first traversal iterates through the tree by going through each level of the tree node-by-node.

## Binary Tree Vs K-ary Trees

- Trees can have any number of children per node
- Binary Trees restrict the number of children to two (hence our left and right children).

### K-ary Trees

If Nodes are able have more than 2 child nodes, we call the tree that contains them a K-ary Tree. In this type of tree we use K to refer to the maximum number of children that each Node is able to have.