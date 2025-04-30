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
Add code here
```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']   
re = [item for item in items if 'e' not  in item]

print(re)
```
## Output

![image](https://github.com/user-attachments/assets/5c300670-6b58-45a3-a922-c7d5c609e12f)

## Result
The expected output is achieved.
