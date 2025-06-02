# 🔁 Queue using Linked List: Display Front and Rear Elements of a Queue

## 🎯 Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---

## 🧠 Algorithm

1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.

---
## Program
      queue = []
      
      queue.append('a')
      queue.append('b')
      queue.append('c')
      queue.append('d')
      
      print("Initial Queue:", queue)
      
      front = queue[0]
      rear = queue[-1]
      
      print("Front element of the queue:", front)
      print("Rear element of the queue:", rear)


## Output
![image](https://github.com/user-attachments/assets/d64f2b27-5c14-46db-835e-b0d9eff22987)

## Result
The program initializes a queue using a list and adds elements 'a', 'b', 'c', and 'd' using the append() method, which simulates enqueue operations. It then prints the entire queue, accesses the front element using queue[0] and the rear element using queue[-1], and displays them. The output correctly shows the queue in order along with its front and rear elements.
