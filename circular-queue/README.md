<h1>
  <span class="headline">Stacks and Queues in Java Lab</span>
  <span class="subhead">Circular Queue</span>
</h1>

## Objective
Write a Java program to implement a circular queue in Java using a fixed-size array.

## Requirements
In this exercise, you will implement a circular queue using a fixed-size array. The circular queue allows efficient usage of space by wrapping around the array when the end is reached.
- Implement a circular queue with the following operations:
   - **enqueue**: Adds an element to the rear of the queue.
   - **dequeue**: Removes and returns an element from the front of the queue.
   - **isEmpty**: Checks if the queue is empty.
   - **isFull**: Checks if the queue is full.
- Use a fixed-size array to store the elements.
- Use two indices, **front** and **rear**, to manage the queue operations.
- Use the `CircularQueue` class in the starter code.
- The starter code includes a set of tests to help you verify your work. To run the tests, right-click on the `CircularQueueTest` class in the `src/test/java` directory and select **Run 'All Tests'**.
   
### Example inputs and expected outputs
**Example 1:**
```java
Queue size: 5
Operations: enqueue(10), enqueue(20), enqueue(30), dequeue(), enqueue(40), enqueue(50), isFull(), enqueue(60)
Output:
Dequeued Element: 10
Queue is full: true
Unable to enqueue, queue is full
```

**Example 2:**
```java
Queue size: 3
Operations: enqueue(1), enqueue(2), dequeue(), dequeue(), isEmpty()
Output:
Dequeued Element: 1
Dequeued Element: 2
Queue is empty: true
```


## Practical relevance
In a linear queue data structure, if the rear reaches to the end position of the Queue then there might be possibility that some vacant spaces are left in the beginning which cannot be utilized. So, to overcome such limitations, the concept of the circular queue was introduced.
- Circular queues are often used in buffering data for hardware or network communications.
- Operating systems use the circular queue to insert the processes and then execute them.
- Computer-controlled traffic lights use circular queue to keep the order of the lights circling indefinitely.
