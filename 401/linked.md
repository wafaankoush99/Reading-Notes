
# Linked Lists

## What is a Linked List

Linked List - A data structure that contains nodes that links/points to the next node in the list.

## Types of Linked Lists:

1. Doubly Linked List : Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.

2. Singly Linked List : Singly refers to the number of reference , It means that is only one reference 

## Terms :

**Node** - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.

*A node only knows about what data it contains, and who its neighbor is.*

**Next** - Each node contains a property called Next. This property contains the reference to the next node. And it is exceptionally important because it will lead us where the next node is and allow us to extract the data appropriately.

**Head** - The Head is a reference of type Node to the first node in a linked list. And is always the first node in a Linked List

**Current** - The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.
And will tell us where exactly in the linked list we are 

***

# data structures

are the different ways that we can organize our data; variables, arrays, hashes, and objects are all types of data structures.


## Types of data structures :

1. linear data structures
2. non-linear data structures

![](https://miro.medium.com/max/700/1*Xokk6XOjWyIGCBujkJsCzQ.jpeg)


**linked lists are linear data structures**

### what makes arrays and linked lists different?

the way that they use memory in our machines
The fundamental difference between arrays and linked lists is that arrays are static data structures, while linked lists are dynamic data structures.
**A static data structure** needs all of its resources to be allocated when the structure is created
**a dynamic data structure** can shrink and grow in memory

Abstraction : simplicity of hiding away things that you don’t need to see or deal with all of the time.

### what allows a linked list to have its memory scattered everywhere?

- linked list doesn’t need a contiguous block of memory

- linked lists can grow and shrink dynamically during a program’s execution

**if we wanted to be able to hop between one node and the node previous without having to go back to the very beginning of the list, a doubly linked list would be a better data structure than a singly linked list.**

**In circular linked list we can turn both a singly linked list and a doubly linked list**

# interview question :

**tell me the how you’d implement X as a linked list, and what the possible drawbacks of that implementation are**

***


## Big O Notation 

**Big O Notation is a way of evaluating the performance of an algorithm. Or is a way to express the amount of time that a function, action, or algorithm takes to run based on how many elements we pass to that function. and most of them involve an O (referred to as just “O” or sometimes as “order”), and a variable n, where n is the size of the input**


There are two major points to consider when thinking about how an algorithm performs

1. how much time it requires at runtime given

2. how much time and memory it needs.

An **O(1) function** takes constant time, which is to say that it doesn’t matter how many elements we have, or how huge our input is: it’ll always take the same amount of time and memory to run our algorithm.

An **O(n) function** is linear, which means that as our input grows (from ten numbers, to ten thousand, to ten million), the space and time that we need to run that algorithm grows linearly.

an **O(n²) function**, which clearly takes exponentially more time and memory the more elements that you have.

Inserting an element at the beginning of a linked list is particularly nice and efficient because it takes the same amount of time, no matter how long our list is, which is to say it has a space time complexity that is constant, or O(1).

• we can insert an element into a linked list: at the very beginning

1. First, we find the head node of the linked list.
2. Next, we’ll make our new node, and set its pointer to the current first node of the list.
3. Lastly, we rearrange our head node’s pointer to point at our new node.

• inserting an element at the end of a linked list 

1. Find the node we want to change the pointer of (in this case, the last node)
2. Create the new node we want to insert and set its pointer (in this case, to null)
3. Direct the preceding node’s pointer to our new node

if we wanted to add an element to the end of a linked list with a billion items! This insert algorithm would take as much time as the number of elements in our list, which, depending on our list, could be a very bad day for us.


[Read 1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)

[Read 2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)



[HomePage](https://wafaankoush99.github.io/Reading-Notes/READMEcode401.html)  


contact wafadirawe@gmail.com

[HomePage](https://wafaankoush99.github.io/Reading-Notes/READMEcode401.html)  


contact wafadirawe@gmail.com