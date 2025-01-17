<h1>
  <span class="headline">Stacks and Queues in Java Lab</span>
  <span class="subhead">Minimum Value Retriever</span>
</h1>

## Objective
Write a Java program to implement using Java’s `Stack` class that supports finding the minimum element in constant time complexity.

## Requirements
- The implemented `MinStack` class must support the following operations:
  1. **push(x):** Push an element `x` onto the stack.  
  2. **pop():** Remove the top element from the stack.  
  3. **top():** Retrieve the top element of the stack.  
  4. **getMin():** Retrieve the minimum element in the stack. This operation must run in **O(1)** time.
- Use the `MinStack` class in the starter code.
- The stack must operate like a normal stack for standard operations (`push`, `pop`, `top`) but also support the `getMin()` operation in constant time.
- You are required to use one or two stacks to achieve this.
- The starter code includes a set of tests to help you verify your work. To run the tests, right-click on the `MinStackTest` class in the `src/test/java` directory and select **Run 'All Tests'**.

### Example inputs and expected outputs
```plaintext
Input:
StackOperations:
1. push(5)
2. push(3)
3. push(8)
4. getMin()
5. pop()
6. getMin()

Output:
3 (after operation #4)
3 (after operation #6)
```

## Practical relevance
- This exercise helps students understand how auxiliary data structures (like `minStack`) enhance algorithm efficiency.
- This exercise encourages a deep dive into stack mechanics and ensures `O(1)` complexity for the `getMin()` operation.
- This exercise strengthens problem-solving through design and validation of custom data structures using test-driven development.
- This exercise is a common interview question to test problem-solving and design abilities.
