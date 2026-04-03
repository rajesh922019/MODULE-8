# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:

n=int(input())

arr=list(map(int, input().split()))

max_score=max(arr)

arr=[x for x in arr if x != max_score]

runner_up=max(arr)

print(runner_up)


## OUTPUT
<img width="1182" height="231" alt="image" src="https://github.com/user-attachments/assets/3bd25931-cf33-4183-b1c0-18751628510a" />

## RESULT

Thus, the python program was successfully exceuted.
