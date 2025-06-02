# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
      stack = []
      for i in range(3):
          stack.append(input())
      print('Insert the first element:')
      print('Insert the second element:')
      print('Insert the third element:')
      print('Initial stack: ' + str(stack))
      
      for i in range(len(stack)):
          top=stack[i]
      
      print("\nElement at the top of the stack is .... ", top)
## Output
![image](https://github.com/user-attachments/assets/0569ee24-d69a-4cd4-b3e3-fd707327e901)

## Result
The program successfully implements a stack using a list, accepts three user inputs, and displays the top element of the stack correctly after insertion.
