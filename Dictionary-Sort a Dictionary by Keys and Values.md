# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
Dict={3:323, 1: 2, 6: 18, 4: 24, 2: 56, 5: 12}
sorted_items=sorted(Dict.items())
print("Keys and Values sorted in alphabetical order by the key")
for k,v in sorted_items:
    print((k,v),end=" ")
```

## Sample Output

<img width="1133" height="177" alt="image" src="https://github.com/user-attachments/assets/786315c9-16e2-44f3-b72f-50fc4f48f9ac" />


## Result

Thus, the program has been successfully executed.
