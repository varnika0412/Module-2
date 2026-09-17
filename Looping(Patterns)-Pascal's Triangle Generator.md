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
Def pascal_triangle(n):
trow = [1] y = [0]
for x in range(max(n,0)):
print(trow)
trow=[l+r for l,r in zip(trow+y, y+trow)]
return n>=1
n=int(input()) pascal_triangle(n)
```
## Sample Output
<img width="472" height="291" alt="image" src="https://github.com/user-attachments/assets/e376f5a4-9a1e-45ca-93ab-a334226b95a1" />

## Result
Thus the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user was successfully completed
