<h1>
  <span class="headline">Stacks and Queues in Java Lab</span>
  <span class="subhead">Parenthesis Balancer</span>
</h1>

## Objective
Write a Java program to determine whether a given string has balanced parentheses using Java’s `Stack` class.

## Requirements

- The program should handle `()`, `{}`, and `[]` brackets.
- A string is considered balanced if:
  - For every opening bracket, there is a corresponding closing bracket of the same type.
  - Brackets are closed in the correct order.
- Use the `ParenthesisBalancer` class in the starter code.
- Use a stack to solve the problem.
- Avoid using libraries other than `java.util.Stack`.
- The starter code includes a set of tests to help you verify your work. To run the tests, right-click on the `ParenthesisBalancerTest` class in the `src/test/java` directory and select **Run 'All Tests'**.
  
### Example inputs and expected outputs
```plaintext
Input: "{[()]}"
Output: true

Input: "{[(])}"
Output: false

Input: "((()))"
Output: true

Input: "[{]}"
Output: false
```

## Practical relevance
- This exercise addresses a common problem in syntax validation, compiler design, and text editors.
- This exercise reinforces understanding of `Stack` operations like `push`, `pop`, and `isEmpty`.