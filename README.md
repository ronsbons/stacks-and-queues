# stacks-and-queues

## Stacks


### Examples


### Questions Solved Using Stacks


## Queues


### Examples
- A line of customers at the grocery store
- A single-lane one-way road
- Call center phone systems
- Printers print jobs in order they're submitted
- Priority queue - values come out in order by priority, instead of FIFO.  An element of highest priority always appears at the front of the queue.  Operating systems use priority queues for load balancing on servers.


### Questions Solved Using Queues
Queues can be helpful in any situation where data doesn't need to be accessed immediately and can be held in a buffer (the queue) or when you need to preserve the order of data, like when selling tickets.  Some example interview questions regarding queues are:
- How to implement a queue using stacks?
- Which data structure is used for breadth-first search (BFS), traversing a tree?


### Deques
Deque is a queue data structure that allows inserting items and deleting items at both ends.  Four basic operations are performed on a deque:
- insertFront(): adds an item at the front of the deque
- insertLast(): adds an item at the rear of the deque
- deleteFront(): deletes an item from the front of the deque
- deleteLast(): deletes an item from the rear of the deque

#### Imnplementation
Deques can be implemented using a doubly linked list or a circular array.  Time complexity in both is O(1).


## Additional Resources
- HackerRank video on [Data Structures: Stacks and Queues](https://www.youtube.com/watch?v=wjI1WNcIntg)