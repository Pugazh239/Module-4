# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
~~~
count = 0
with open("story.txt", "r") as file:
    for line in file:
        if line.strip() and not line.lstrip().startswith('T'):
            count += 1
print("Sum :", count)
~~~


## Output
![445986945-3fdf4415-066c-4b15-8952-ecc2d17720ab](https://github.com/user-attachments/assets/9adea877-a754-4155-afb5-92b695c221f0)


## Result
Thus the program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T' is executed successfully.
