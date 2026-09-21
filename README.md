## 🎯 Aim

To write a Python program to calculate the final amount paid by Vimla for purchasing a microwave oven after applying a discount and adding CST.


## 🧠 Algorithm

1. Start the program
2. Initialize the amount of the microwave oven as Rs.25,000.
3. Read the discount percentage (5%) and CST percentage (2%).
4. Calculate the discount amount:
         discount_amount=discount_percentage/100*amount
5. Calculate the CST amount:
         cst_amount=cst_percentage/100*amount
6. Calculate the final amount to be paid:
      final_amount=amount+cst_amount-discount_amount
7. Display the final amount.
8. Stop the program. 
---

## 💻 PROGRAM:
```
amount=25000
discount_percentage=5
cst_percentage=2
discount_amount=(discount_percentage/100)*amount
cst_amount=(cst_percentage/100)*amount
final_amount=amount+cst_amount-discount_amount
print(final_amount)
```
## OUTPUT

<img width="1183" height="190" alt="image" src="https://github.com/user-attachments/assets/17e2e2e8-1a19-4e35-b2b8-90535b79f63e" />

## RESULT
Hence Calculated total marks for students and find the topper.

# 🔄 Hackerrank : # Star Pattern Printer
## 🎯 Aim

To write a Python program to construct a star pattern in an increasing and then decreasing order based on the given number n.

## 🧠 Algorithm
1.Start the program.
2.Read an integer n from the user (number of rows for the upper half).
3.Use a for loop from 1 to n:
   Print * repeated i times.
4.Use another for loop from n-1 down to 1:
   Print * repeated i times.
5.End the program.

## 🧪 Program
```
n=int(input())
for i in range(1, n+1):
    print('* ' * i)
for i in range(n-1, 0, -1):
    print('* ' * i)
```
 
## Sample Output

<img width="1187" height="395" alt="image" src="https://github.com/user-attachments/assets/566fa0fb-575e-4613-af22-3eab0f819070" />


## Result
Thus, the python program was successfully executed.

# 🎓 Hackerrank:Python Program to Find Students with the Second Lowest Grade

This program reads student names and their corresponding grades, identifies the **second lowest grade**, and prints the names of all students who have that grade in **alphabetical order**.

---

## 🎯 Aim

To write a Python program to:
- Read a list of students and their grades.
- Identify the second lowest grade.
- Print the names of students who have that grade, sorted alphabetically.

---

## 🧠 Algorithm

1. **Read** an integer `n` representing the number of students.
2. **Read** each student’s name and grade, and store them as a sublist inside a list.
3. **Extract** all the grades and sort them.
4. **Identify** the second lowest grade from the sorted grade list.
5. **Collect** names of all students whose grade matches the second lowest grade.
6. **Sort** the names alphabetically.
7. **Print** each name on a new line.

---

## 💻  Program
```
l1=[]
l2=[]
for _ in range(int(input())):
    name = input()
    score = float(input())
    l1.extend([name, score])
    l2.append(l1)
    l1=[]
l3=[]
l4=[]
for i in l2:
    l3.append(i[1])
l3.sort()
for i in l2:
    if i[1]==l3[1]:
        l4.append(i[0])
l4.sort()
for i in l4:
    print(i)
```
## Output

<img width="1185" height="438" alt="image" src="https://github.com/user-attachments/assets/f9fd95cc-e206-4ebc-a889-9afe0904b195" />


## Result
Thus, the python program was exceuted successfully.

# 🎓 Hackerrank:Runner-Up Score Finder
## 🎯 Aim
To write a Python program to find the runner-up score (second highest) from a given list of scores.

## 🧠 Algorithm
1. Start the program.
2. Read an integer n (number of scores).
3. Read the list of n integers separated by space.
4. Find the maximum score from the list.
5. Remove all occurrences of the maximum score from the list.
6. Find the maximum score from the remaining list → this will be the runner-up score.
7. Print the runner-up score.
8. Stop.

## 💻  Program
```
n=int(input())
arr=list(map(int, input().split()))
max_score=max(arr)
arr=[x for x in arr if x != max_score]
runner_up=max(arr)
print(runner_up)
```

## Output

<img width="1182" height="231" alt="image" src="https://github.com/user-attachments/assets/fa7129a3-bc02-49ef-98c5-e9bc66c95a89" />


## Result

Thus, the python program was successfully exceuted.

# 🔍 Hackerrank:Python Program to Check if a String Ends with a Numeric Digit

This Python program checks whether the last character of a given input string is a **numeric digit (0–9)**.

---

## 🎯 Aim

To write a Python program that checks if a given string ends with a number using Python's built-in string methods.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Input** a string from the user.
3. **Access** the last character using indexing (`string[-1]`).
4. **Check** if the last character is a digit using the `.isdigit()` method.
5. **If true**, print that the string ends with a number.
6. **Else**, print that the string does not end with a number.
7. **End the program.**

---

## 💻  Program
```
import re

s = input()
p = '[a-zA-Z0-9]*[0-9]+'
x = re.match(p, s)

if x:
    print("True")
else:
    print("False")
```
## Output
![image](https://github.com/user-attachments/assets/7ddc3249-b794-4293-8464-501b03bb0a3c)

## Result
Thus the program has been successfully executed



