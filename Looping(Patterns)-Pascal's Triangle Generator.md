# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.



## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.



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



## 🧪 Program
```
size=int(input())
m=(2*size)-2
for i in range(0,size):
    for j in range(0,m):
        print(end=" ")
    m=m-1
    for j in range(0,i+1):
        print("* ",end=' ')
    print(" ")
```

## Sample Output
![image](https://github.com/user-attachments/assets/5c585d1e-78a8-4abd-a51f-1961778ffa9a)


## Result
Thus the program executed successfully.

