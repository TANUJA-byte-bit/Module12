# 12e)  Stack using Linked List: Stack Implementation (Top Element Display)

##  Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

##  Algorithm

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

##  Program
```
stack = []
stack.append(input("Insert the first element:"))
stack.append(input("\nInsert the second element:"))
stack.append(input("\nInsert the third element:"))
print('\nInitial stack: ' + str(stack))
for i in range(len(stack)):
    top=stack[i]
print("\nElement at the top of the stack is .... ", top)
```
## Output
<img width="986" height="288" alt="image" src="https://github.com/user-attachments/assets/e7729bc8-d172-4f77-912b-2557f4f7fae1" />

## Result
Program executed Successfully.
