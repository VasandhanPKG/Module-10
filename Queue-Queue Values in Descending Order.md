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

```
q = []
  n = int(input("Enter the number of elements to add to the queue: "))
  
  for i in range(n):
      val = int(input(f"Enter element {i+1}: "))
      q.append(val)
  
  if len(q) >= 2:
      q.pop(0)
      q.pop(0)
  elif len(q) == 1:
      q.pop(0)

  q.sort(reverse=True)
  print("Remaining elements in descending order:", q)
```

### Output:
![image](https://github.com/user-attachments/assets/def370d6-1b01-4663-ad0b-497a12f14adb)

## Result:
Thus, the program has been execueted successfully.
