# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
msg="You're out of list range"
List=[10,20,30]
try:
    print(List[5])
except IndexError:
    print(msg)
```

## Output

<img width="736" height="150" alt="image" src="https://github.com/user-attachments/assets/add1fa3e-c50f-46b2-8678-c6a6e788e5ab" />


## Result
Thus, the program has been successfully executed.
