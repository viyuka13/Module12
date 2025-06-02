# # 📚 Stack using Linked List: Check and Display Whether the Stack is Full or Not

This Python program demonstrates how to check if a stack (using `LifoQueue` from the `queue` module) is full or not. It uses the `full()` method to determine the stack's status and then displays the appropriate message.

## 🎯 Aim

To write a Python program that:
- Creates a stack with a fixed size.
- Adds elements to the stack.
- Checks if the stack is full.
- Displays a message indicating whether the stack is full or not.

## 🧠 Algorithm

1. **Import the LifoQueue class**:
   - Import `LifoQueue` from the `queue` module to create the stack.

2. **Create a Stack**:
   - Instantiate a `LifoQueue` with a maximum size (e.g., 4).

3. **Add Elements to the Stack**:
   - Add elements (e.g., 'a', 'b', and 'c') to the stack using the `put()` method.

4. **Check if the Stack is Full**:
   - Use the `full()` method of `LifoQueue` to check if the stack has reached its maximum capacity.

5. **Display the Status**:
   - Print "Stack is full" if the stack is full.
   - Otherwise, print "Stack is not full".

## 📝 Program
      from queue import LifoQueue
      
      stack = LifoQueue(maxsize=4)
      
      stack.put('a')
      stack.put('b')
      stack.put('c')
      if stack.full():
          print("Stack if full")
      else:
          print("Stack is not full")


## Sample Input & Output
![image](https://github.com/user-attachments/assets/999d2cd5-3da6-4218-971f-6eb81ebb65d6)

## Result
The program imports the LifoQueue class from Python’s queue module to implement a stack (Last-In-First-Out structure) with a maximum size of 4. It pushes elements 'a', 'b', and 'c' onto the stack using the put() method. It then checks if the stack is full using the full() method. Since only three elements have been added, the condition evaluates to false, and the output correctly indicates that the stack is not full.

