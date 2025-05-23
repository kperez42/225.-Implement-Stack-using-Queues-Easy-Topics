# 225.-Implement-Stack-using-Queues-Easy-Topics
 📘 Problem Description  Implement a **Last-In-First-Out (LIFO)** stack using only **queue** operations. Your implementation should support the following standard operations:  - `push(x)` – Push element x onto stack. - `pop()` – Removes the element on top of the stack and returns it.  
This solution uses a single queue and simulates stack behavior by rotating the queue:

When pushing a new element, it's added to the back of the queue.

Then, the entire queue is rotated so the new element moves to the front.

This guarantees that top() and pop() work like a real stack.

🧠 Time Complexity
push(x) – O(n)

pop() – O(1)

top() – O(1)

empty() – O(1)

🧠 Space Complexity
O(n) — to store the elements in the queue

