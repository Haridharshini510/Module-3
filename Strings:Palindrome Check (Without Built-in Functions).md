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
rev = s[::-1]

if s == rev:
    print("The string is a Palindrome")
else:
    print("The string is not a Palindrome")

```

## Output
<img width="538" height="247" alt="image" src="https://github.com/user-attachments/assets/7d6d1e88-8f6a-4658-bb30-fc9d091a5ff1" />

## Result
Thus, the program was executed successfully and the given string was checked for palindrome condition.
