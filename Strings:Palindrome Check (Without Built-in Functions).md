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
s = "google"
reversed_s = s[::-1]
if s == reversed_s:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```
## Output
![Screenshot 2025-05-01 093327](https://github.com/user-attachments/assets/c7f08964-8139-4bd2-b930-9adec1fa7299)

## Result
Thus,the python program excuted successful
