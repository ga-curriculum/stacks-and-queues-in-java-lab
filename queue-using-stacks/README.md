<h1>
  <span class="headline">Stacks and Queues in Java Lab</span>
  <span class="subhead">Queue Using Stacks</span>
</h1>

## Objective
Write a Java program to implement a queue using two stacks. A queue is a FIFO (First-In-First-Out) data structure, while a stack is a LIFO (Last-In-First-Out) data structure. By combining two stacks, you will create a queue-like behavior.

## Requirements
- Use two stacks (`stack1` and `stack2`) implemented with arrays.
- Implement the following operations:
   - `enqueue(int data)`: Insert an element into the queue.
   - `dequeue()`: Remove an element from the front of the queue.
   - `peek()`: Get the front element without removing it.
   - `isEmpty()`: Check if the queue is empty.
- If `dequeue` or `peek` is called on an empty queue, print an appropriate error message (e.g., "Queue is empty").  
- Use fixed-sized arrays for both stacks (initial size 10). Resize the array if necessary.
- Use the `QueueUsingTwoStacks` class in the starter code.
- The starter code includes a set of tests to help you verify your work. To run the tests, right-click on the `QueueUsingTwoStacksTest` class in the `src/test/java` directory and select **Run 'All Tests'**.
   
### Example inputs and expected outputs
1. **Input:**  
   `enqueue(10), enqueue(20), enqueue(30), dequeue(), peek(), isEmpty()`  
   **Output:**  
   ```
   10
   20
   false
   ```

2. **Input:**  
   `dequeue(), dequeue(), isEmpty()`  
   **Output:**  
   ```
   Queue is empty
   Queue is empty
   true
   ```


## Practical relevance
This exercise will:
1. Help in understanding the interplay between data structures (queue emulation via stacks) which is critical for algorithms.
2. Reinforce array manipulation techniques and edge case handling.