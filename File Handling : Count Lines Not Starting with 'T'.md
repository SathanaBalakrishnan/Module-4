# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
python program:
file=open("story.txt","r") 
count=0 
for lines in file: 
   if lines [0] not in 'T': 
      count+=1 
print(count)

css
story.txt:
This is a tale
Once upon a time
The sun rises
apple is sweet
```

## Output

<img width="1920" height="1080" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/c681a463-52c1-4817-ad5a-40ab3b666121" />

## Result
Thus the program executed successfully.
