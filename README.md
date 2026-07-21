# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
<img width="240" height="116" alt="image" src="https://github.com/user-attachments/assets/70f15746-5119-4cbf-9a7e-519f7afdc3dd" />


## Output
<img width="268" height="150" alt="image" src="https://github.com/user-attachments/assets/ad223a1c-7afb-4d89-b1a7-b13c8c387909" />

## Result
Thus a Python program that calculates the sum of all elements in a list is created.

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)

```
## Output
<img width="717" height="203" alt="image" src="https://github.com/user-attachments/assets/3c87b67b-46ba-44c9-aa18-0c505372976f" />

## Result
Thus the program executed successfully.

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```
## Output

<img width="802" height="244" alt="Screenshot 2026-04-21 132401" src="https://github.com/user-attachments/assets/83cf4ad4-65ba-40cc-8643-780559135312" />

## Result
Thus the program executed successfully.
