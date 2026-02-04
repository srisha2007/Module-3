# Regex in Python: Filter Words Without the Letter 'e'

## Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## Program
```
import re
words = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
filtered_words = [word for word in words if not re.search('e', word)]

print(filtered_words)

```

## Output

<img width="206" height="150" alt="image" src="https://github.com/user-attachments/assets/1a3ecc1d-38cf-4cad-9e05-372af3260a4c" />

## Result
Thus the program executed successfully.

