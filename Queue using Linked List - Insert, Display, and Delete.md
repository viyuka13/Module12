# 🌀 Queue using Linked List - Insert, Display, and Delete

## 🎯 Aim

To write a Python program that:
- Inserts elements into a queue.
- Displays all inserted elements.
- Deletes the first element.
- Displays the updated queue after deletion.

---

## 🧠 Algorithm

1. **Create a Queue**:
   - Initialize an empty list named `queue`.

2. **Insert Elements**:
   - Use the `append()` method to insert elements `'a'`, `'b'`, and `'c'` into the queue.

3. **Display Initial Queue**:
   - Print the message `"Queue after elements are inserted:"` followed by the queue contents.

4. **Delete First Element**:
   - Use `pop(0)` to remove the first inserted element (FIFO - First In First Out).
   - Print the message `"Deleting the first element inserted:"` and the element removed.

5. **Display Updated Queue**:
   - Print the message `"Queue after the first element is deleted:"` followed by the updated queue contents.

---

## Program
      stack = []
      
      stack.append('a')
      stack.append('b')
      stack.append('c')
      print("Stack after elements are pushed:")
      print(stack)
      print("Deleting the last element inserted:")
      
      print(stack.pop())
      print("Stack after elements are popped:")
      print(stack)

## Output
![image](https://github.com/user-attachments/assets/1137acf9-f064-4588-b65e-052b4d5f626e)

## Result
The program defines a Python list to simulate a queue and uses FIFO (First In First Out) behavior. It inserts elements 'a', 'b', and 'c' into the queue using the append() method, and removes the first inserted element using pop(0). The program correctly displays the queue before and after deletion, showing the updated state of the queue. The output confirms that the queue operations were performed as expected.
