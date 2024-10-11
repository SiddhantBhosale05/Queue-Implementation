# Queue Implementation
Experiment 19

## Aim 
To implement queue.


## Theory
#### Definition

A queue is a linear data structure that follows the First In, First Out (FIFO) principle. This means that the first element added to the queue will be the first one to be removed. Queues are widely used in various applications, such as scheduling processes, managing requests in a service, and handling asynchronous data.

#### Key Characteristics 

- **FIFO Structure**: The first element added to the queue is the first to be removed.
  
#### Operations

- **Enqueue**: Add an element to the rear of the queue.
- **Dequeue**: Remove and return the front element of the queue.
- **Peek/Front**: Return the front element without removing it.
- **isEmpty**: Check if the queue is empty.
- **isFull**: Check if the queue is full (only applicable in fixed-size queues).

#### Implementation

Queues can be implemented using two primary methods: arrays and linked lists.
eg-
```cpp
struct Queue {
    int arr[MAX]; // Array to hold queue elements
    int front;    // Index of the front element
    int rear;     // Index of the rear element
};
```
