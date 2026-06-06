# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
n = int(input())

for i in range(n):
    print(" " * (n - i), end="")
    c = 1
    for j in range(i + 1):
        print(c, end=" ")
        c = c * (i - j) // (j + 1)
    print()
```

## Output

<img width="376" height="247" alt="image" src="https://github.com/user-attachments/assets/065bbc06-5254-4185-9246-39d2bc7a920a" />

## Result
Thus, the Python program to generate Pascal's Triangle using numbers for the given number of rows was successfully executed and the desired output was obtained.


