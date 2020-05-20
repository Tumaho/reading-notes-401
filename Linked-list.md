# Linked list

## A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.There are two types of Linked List :

1- Singly :  there is only one reference, and the reference points to the Next node in a linked list.

2- Doubly : there is a reference to both the Next and Previous node.

### Node 

#### Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.

### Next

#### Each node contains a property called Next. This property contains the reference to the next node.

### Head

#### The Head is a reference type of type Node to the first node in a linked list.

### Current

#### The Current reference is a reference type of type Node that is currently being looked at. This node is traditionally used when traversing through a full linked list. When traversing, you typically reset the current to the head to guarantee you are starting from the beginning of the linked list.


## Traversal

### When traversing a linked list, you are not able to use a foreach or for loop. We depend on the Next value in each node to guide us where the next reference is pointing. The Next property is exceptionally important because it will lead us where the next node is and allow us to extract the data appropriately.

## Big O

### The Big O of time for Includes would be O(n). This is because, at its worse case, the node we are looking for will be the very last node in the linked list. n represents the number of nodes in the linked list.