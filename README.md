## NAME: Thaarakeshwar
## REGISTER NO: 212225040466

## EX 11:List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
numbers = [10, 20, 30, 40, 50]

total = sum(numbers)

print(f"The list elements are: {numbers}")
print(f"The sum of all elements in the list is: {total}")
```
## Output

<img width="511" height="194" alt="{E6DA6F42-8FE5-4035-9874-7AD3FDD0CD47}" src="https://github.com/user-attachments/assets/f361a676-7029-40a7-adaa-1fce4c167ed4" />

## Result
Thus, the Python program to calculate the sum of all elements in a list using the built-in sum() function was successfully implemented and executed, and the output was verified.

## EX 12:Regex in Python: Filter Words Without the Letter 'e'

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

print(f"The original list is: {items}")
print(f"The words that do not contain the letter 'e' are: {l1}")
```
## Output

<img width="834" height="188" alt="{E4EE54E7-D33F-42D0-A3D1-04EE38485F17}" src="https://github.com/user-attachments/assets/3b0932f9-eb2f-4361-a3bf-2aabfb6ba073" />

## Result
Thus, the Python program to filter and display words that do not contain the letter 'e' using regular expressions was successfully implemented and executed, and the output was verified.

## EX 13:🧹 Strings-Remove Nth Index Character from a String

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
def remove(s):
    n = int(input("Enter the index to remove: "))
    a = ""

    for i in range(len(s)):
        if i != n:
            a += s[i]

    return a

s = input("Enter a string: ")

print(f"The modified string is: {remove(s)}")
```
## Output

<img width="472" height="220" alt="{F7F23A2B-D466-45E2-8B35-ADE7BEA66765}" src="https://github.com/user-attachments/assets/37354af3-3b94-4aa9-a3f3-1d3ce9a7b264" />

## Result
Thus, the Python program to remove a character at a specified index from a string was successfully implemented and executed, and the output was verified.

## EX 14:Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
s = "google"

rev = s[::-1]

if s == rev:
    print(f"The string '{s}' is a palindrome")
else:
    print(f"The string '{s}' is not a palindrome")
```
## Output

<img width="541" height="213" alt="{0911D2B8-BCD4-458F-8936-1D482F4929EE}" src="https://github.com/user-attachments/assets/8da766a3-045d-4946-b46a-20d50e5ec37c" />

## Result
Thus, the Python program to check whether the string "google" is a palindrome using string slicing was successfully implemented and executed, and the output was verified.

## EX 15:Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
x = ('a', 'n', 'k', 5, 8, 10)

print(f"Tuple elements are: {x}")
print(f"Is 'n' present in the tuple? {('n' in x)}")
print(f"Is 8 present in the tuple? {(8 in x)}")
```
## Output

<img width="540" height="253" alt="{8E70BF91-FD2D-4B59-A5E3-F7EBC08455EA}" src="https://github.com/user-attachments/assets/0d262f20-7a20-42b5-8050-beeb1ad53f1c" />

## Result
Thus, the Python program to check the presence of elements 'n' and 8 in a tuple using the in operator was successfully implemented and executed, and the output was verified.
