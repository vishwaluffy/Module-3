# Tuple in Python: Check Element Existence

## 🎯 Aim
To Write a python program to create the tuple by the multiples of 5 up to N. Get the N value from the user.

## 🧠 Algorithm
1. Start.
2. Prompt the user to enter a number N.
3. Initialize an empty list to store the multiples.
4. Use a loop to iterate from 1 to N (inclusive).
5. For each number, check if it is divisible by 5 (i.e., number % 5 == 0). 
6. If true, add it to the list.
7. Convert the list to a tuple.
8. Print the resulting tuple




## 🧾 Program
Add code here
```
num = eval(input())

num1=[]
for i in range(5,num,5):
    num1.append(i)
    
print(tuple(num1))
```

## Output

![image](https://github.com/user-attachments/assets/3119fe1f-1daf-4294-bd8a-a6d288c0b85a)


## Result
The expected output is achieved.
