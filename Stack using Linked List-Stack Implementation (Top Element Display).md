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
~~~
stack = []  
for i in range(3):
    element = input(f"Enter element {i+1}: ")
    stack.append(element)

if len(stack) > 0:
    print("Stack:", stack)
    print("Top element:", stack[-1])
else:
    print("Stack is empty")
~~~

## Output
<img width="395" height="252" alt="image" src="https://github.com/user-attachments/assets/0481a283-8b16-4baf-84ce-3e7f02e99b85" />

## Result
Thus, the program has been execueted successfully.
