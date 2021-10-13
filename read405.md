# Big O
Big o used to describe the efficacy of algorithm by measure to factor

1) Running Time ( complexity):
 amount of time a function needs to complete.

2) Memory Space (complexity)
amount of memory uses to store data and instructions.
 

 we can analyze and determine these factor by foy kays:

- Input Size
- Units of Measurement
- Orders of Growth
- Best Case, Worst Case, and Average Case

### Input Size

Account the size of each parameter value as well . so the larger the input size usually results in more time and space

### Units of Measurement

It's a way to measure complexity (space and time).

- The time in milliseconds from the start of a function execution until it ends.

- The number of operations that are executed.

- The number of “Basic Operations” that are executed.

Memory Space, quantify  :

- amount of space needed to hold the code.
- amount of space needed for the input data.
- amount of space needed for the output data.
-  amount of space needed to hold the working space inlcuding stack space to avoid stack overflow.

### Orders of Growth

the overall efficiency by using input size

![alt tag](img/OrdersOfGrowth.png)

- Linked lists consists of memory allocations .

- To address an element of linked list we just need to rearrange our pointers


# Linked Lists

### What is a Linked List

a sequence of Nodes that are connected to each other which mean Node references the next Node

###  types of Linked List

- Singly 
- Doubly

### Traversal

When traversing a linked list, you are not able to use a foreach or for loop. We depend on the Next value in each node to guide us where the next reference is pointing.

The best way to approach a traversal is through the use of a while() loop.:

Example 


ALGORITHM Includes (value)
// INPUT <-- integer value
// OUTPUT <-- boolean

  Current <-- Head

  WHILE Current is not NULL
    IF Current.Value is equal to value
      return TRUE

Current <-- Current.Next
 return FALSE


