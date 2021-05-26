# Stacks and Queues

## What is a Stack

A stack is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.

***Common terminology for a stack is***

**Push** - Nodes or items that are put into the stack are pushed

**Pop** - Nodes or items that are removed from the stack are popped. When you attempt to pop an empty stack an exception will be raised.

**Top** - This is the top of the stack.

**Peek** - When you peek you will view the value of the top Node in the stack. When you attempt to peek an empty stack an exception will be raised.

**IsEmpty** - returns true when stack is empty otherwise returns false.


***

### What are these concepts mean? 
1. FILO 
2. LIFO

***

1. FILO (First In Last Out)

This means that the first item added in the stack will be the last item popped out of the stack.

2. LIFO (Last In First Out)

This means that the last item added to the stack will be the first item popped out of the stack.

***
the topmost item is denoted as the top. When you push something to the stack, it becomes the new top. When you pop something from the stack, you pop the current top and set the next top as top.next.

![](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/stack1.PNG)


***
Push O(1)
Pushing a Node onto a stack will always be an O(1) operation. This is because it takes the same amount of time no matter how many Nodes (n) you have in the stack.

***

Pop O(1)
Popping a Node off a stack is the action of removing a Node from the top. When conducting a pop, the top Node will be re-assigned to the Node that lives below and the top Node is returned to the user.

***

Peek O(1)
When conducting a peek, you will only be inspecting the top Node of the stack.

***

## What is a Queue 

Common terminology for a queue is

- Enqueue - Nodes or items that are added to the queue.
- Dequeue - Nodes or items that are removed from the queue. If called when the queue is empty an exception will be raised.
- Front - This is the front/first Node of the queue.
- Rear - This is the rear/last Node of the queue.
- Peek - When you peek you will view the value of the front Node in the queue. If called when the queue is empty an exception will be raised.
- IsEmpty - returns true when queue is empty otherwise returns false.

***

Enqueue O(1)
When you add an item to a queue, you use the enqueue action. This is done with an O(1) operation in time because it does not matter how many other items live in the queue (n); it takes the same amount of time to perform the operation.

***

Dequeue O(1)
When you remove an item from a queue, you use the dequeue action. This is done with an O(1) operation in time because it doesn’t matter how many other items are in the queue, you are always just removing the front Node of the queue.

***

Peek O(1)
When conducting a peek, you will only be inspecting the front Node of the queue.

***

Queue Visualization

![](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/Queue.PNG)

***

[Details](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)

[HomePage](https://wafaankoush99.github.io/Reading-Notes/READMEcode401.html)  


contact wafadirawe@gmail.com