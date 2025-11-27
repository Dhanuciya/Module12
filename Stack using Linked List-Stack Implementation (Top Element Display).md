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
stack.append('a') 
stack.append('b') 
stack.append('c') 
print ('Initial stack: ' + str(stack))
for i in range(len(stack)): 
    print(i,stack[i])
~~~

## Output
<img width="546" height="177" alt="image" src="https://github.com/user-attachments/assets/9f937411-a856-45ca-bce1-09580f81b31b" />

## Result
Thus, the program has been execueted successfully.
