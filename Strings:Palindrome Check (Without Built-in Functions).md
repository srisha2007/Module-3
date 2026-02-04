# Strings-Palindrome Check in Python (Without Built-in Functions)

##  Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

##  Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

##  Program

```
s = "google"
left = 0
right = len(s) - 1
is_palindrome = True
while left < right:
    if s[left] != s[right]:
        is_palindrome = False
        break
    left += 1
    right -= 1
if is_palindrome:
    print(f'"{s}" is a palindrome')
else:
    print(f'"{s}" is not a palindrome')

```
## Output
<img width="344" height="147" alt="image" src="https://github.com/user-attachments/assets/af49e26f-207f-4b0c-9d42-1e733bc104a7" />

## Result
Thus the program executed successfully.

