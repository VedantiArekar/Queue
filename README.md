# Queue

A queue in C is basically a linear data structure to store and manipulate the data elements. It follows the order of First In First Out (FIFO).

In queues, the first element entered into the array is the first element to be removed from the array.

For example, let’s consider the scenario of a bus-ticket booking stall. Here, the fashion of a C programming queue is followed. The tickets are distributed on the first-come-first-serve basis i.e. the first one to enter is the first one to be served with the tickets.

A queue is open at both ends. One end is provided for the insertion of data and the other end for the deletion of data.

A queue can be implemented with any programming language such as C, Java, Python, etc.

![image](https://user-images.githubusercontent.com/125825670/234075507-d780f6e9-c121-4a7c-9fb8-6ad89a6b2648.png)

Operations Associated with a Queue in C

A queue being an Abstract Data Structure provides the following operations for manipulation on the data elements:

1. isEmpty(): To check if the queue is empty

2. isFull(): To check whether the queue is full or not

3. dequeue(): Removes the element from the frontal side of the queue

4. enqueue(): It inserts elements to the end of the queue

Front: Pointer element responsible for fetching the first element from the queue

Rear: Pointer element responsible for fetching the last element from the queue
