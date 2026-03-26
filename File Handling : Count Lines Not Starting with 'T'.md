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
f = open("story.txt", "r")
count = 0
for line in f:
    if not line.startswith('T'):
        count += 1
f.close()
print(count)
~~~
## Output
<img width="623" height="365" alt="Screenshot 2026-03-26 111712" src="https://github.com/user-attachments/assets/0d3de03d-1501-4f41-9ab6-be9bc8c2cd9c" />

## Result
Thus,the program has been executed successfully.
