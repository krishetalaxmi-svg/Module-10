# Queue-Queue Values in Descending Order Using Python 🧮

This Python program simulates a queue using a list, removes the first two elements (FIFO order), and displays the remaining values in descending order.

## 🎯 Aim

To write a Python program to:
- Accept user inputs into a list (queue)
- Remove the first two elements (simulating dequeue)
- Display the remaining values in **descending order**

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` to determine how many elements will be added.
3. Loop `n` times:
   - Read an input value.
   - Append it to the list `q`.
4. Remove the first element using `pop(0)`.
5. Remove the second element using `pop(0)` again.
6. Sort the list in descending order.
7. Print the updated list.

## 🧪 Program: 
      from queue import PriorityQueue  
      q = PriorityQueue()  
      n=int(input())
      for i in range(n):
          l=input().split(',')
          q.put((l[0],l[1])) 
        
      while not q.empty():  
          next_item = q.get()  
          print(next_item)
### Output:
<img width="1183" height="342" alt="image" src="https://github.com/user-attachments/assets/5594731d-432d-4e38-93d9-f4f6945c104d" />

## Result:
Thus the program is verified.

# Queue-Remove Two String Values from the Rear End in Python 🧵

This Python program demonstrates how to manage a list of strings and remove the last two elements (i.e., from the rear of the list).

## 🎯 Aim

To write a Python program to:
- Accept `n` string values from the user
- Remove the last two values (rear end of the list)
- Display the updated list

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` from the user (number of strings).
3. Loop `n` times:
   - Read a string input.
   - Append it to the list `q`.
4. Remove the last element using `pop()`.
5. Remove the next last element using `pop()` again.
6. Display the updated list.

##  Program:
      from collections import deque
      q=deque()
      n=int(input())
      for i in range(n):
          q.append(input())
      for i in range(2):
          q.popleft()
      print(q)
      )

### Output:
<img width="1187" height="399" alt="image" src="https://github.com/user-attachments/assets/70ff0276-685b-444a-acfb-36f1bed562dc" />

## Result:
Thus the program is verified.
