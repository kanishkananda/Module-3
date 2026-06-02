## Name: N.Kanishka 
## Register no:212225230127
# List Operations in Python: Sum of List Items

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
print("Sum of the list items is:", total)
```
## Output
<img width="1037" height="771" alt="image" src="https://github.com/user-attachments/assets/bbb51650-a636-4bc1-95da-9af24c069643" />

## Result
Thus To write a Python program that calculates the sum of all elements in a list has been executed sucessfully.


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

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1 = []

for i in items:
    if not re.search(r'e', i):
        l1.append(i)

print("Filtered words without 'e':", l1)
```
## Output
<img width="1071" height="889" alt="image" src="https://github.com/user-attachments/assets/4ecadbf4-c573-4cd1-af68-ed7f33b6b826" />

## Result
Thus To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) has been executed sucessfully.


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
def remove(string):
    n = int(input("Enter the index to remove: "))
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    return a

input_string = input("Enter a string: ")
result = remove(input_string)
print("String after removal:", result)
```

## Output
<img width="1037" height="812" alt="image" src="https://github.com/user-attachments/assets/331cb4d4-51ec-4509-a69d-1b680a0b994f" />

## Result
Thus To write a Python program that accepts a string and removes the character at a specified index has been executed sucessfully


# Strings-Palindrome Check in Python (Without Built-in Functions)

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
string = "google"
reversed_string = string[::-1]

if string == reversed_string:
    print(f'"{string}" is a palindrome.')
else:
    print(f'"{string}" is not a palindrome.')
```
## Output
<img width="1036" height="787" alt="image" src="https://github.com/user-attachments/assets/2e676fa6-d9b7-4abc-8003-2edcb4ed9053" />

## Result
 Thus To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions has been executed sucessfully.


 # Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
x = ('a', 'b', 'n', 4, 8, 9)

# Check if 'n' exists
exists_n = 'n' in x
# Check if 8 exists
exists_8 = 8 in x

print(f"'n' exists in tuple: {exists_n}")
print(f"8 exists in tuple: {exists_8}")
```
## Output
<img width="1127" height="886" alt="image" src="https://github.com/user-attachments/assets/86bf7cad-9eaa-48cd-9c14-51c1b19618ef" />

## Result
Thus To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple has been executed sucessfully.
