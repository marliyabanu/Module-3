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

word = "google"
reversed_word = word[::-1]

if word == reversed_word:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")


## Output
<img width="1275" height="377" alt="image" src="https://github.com/user-attachments/assets/60991c45-4db7-478a-94aa-153993f2c151" />


## Result
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions is excuted sucessful.
