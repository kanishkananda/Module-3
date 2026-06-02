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
