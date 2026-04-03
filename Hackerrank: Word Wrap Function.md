# 🔄 Hackerrank : # 📦 Python Word Wrap Function

This Python program defines a function that **wraps a long string into multiple lines**, ensuring each line does not exceed a specified width.

---

## 🎯 Aim

To write a Python function that takes a long string and a specified width, and returns the string formatted with line breaks such that each line has **at most the given width**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Define a function `wrap(string, max_width)`:
   - Create an empty list `wrapped_lines` to store parts of the string.
   - Loop through the string using steps of `max_width`.
   - In each iteration, extract a substring of length `max_width`.
   - Append this substring to the list.
3. Join the list with `\n` to create the final string.
4. Return the result.
5. **End** the program.

---


## 🧪 Program

n=int(input())

for i in range(1, n+1):

    print('* ' * i)
    
for i in range(n-1, 0, -1):

    print('* ' * i)

## Sample Output
<img width="1187" height="395" alt="image" src="https://github.com/user-attachments/assets/5e1c6945-067a-4b0b-b446-3cbd301540f3" />

## Result

Thus, the python program was successfully executed.
