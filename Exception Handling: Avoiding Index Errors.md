# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
~~~
lis=[5, 10, 20]
try:
    print(lis[5])
except:
    print("You're out of list range")
~~~


## Output
![445982900-c3672b00-e854-4b8b-8b38-6fa62cdf3ff1](https://github.com/user-attachments/assets/312b9d01-2bb9-4c81-9fb2-27b723cfbbde)


## Result
Thus the program that handles an IndexError when trying to access an element beyond the available range of a list is executed successfully
