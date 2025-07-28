# 🟡 Add Two Numbers

**Problem link:** [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)  
**Difficulty:** Medium  
**Runtime:** 5 ms  
**Memory Usage:** 17.8 MB  

### 🧠 Approach
- We simulate digit-by-digit addition like how we do it manually.
- Start from the least significant digit (head of the list).
- Traverse both input lists while maintaining a carry value.
- For each step, add the two digits and the carry, and create a new node with `val % 10`.
- Update the carry as `val // 10`.
- Continue until all digits and the carry are handled.
