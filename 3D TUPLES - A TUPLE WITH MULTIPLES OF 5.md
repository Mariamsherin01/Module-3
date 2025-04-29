# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
reg.no: 212222060143
name: Mariam Sherin
a=int(input())
b=[]
for i in range(1,a):
    if i%5==0:
        b.append(i)
print(tuple(b))
        
```

### OUTPUT
![image](https://github.com/user-attachments/assets/b01ba55d-5f74-4234-be39-e9843a98b74d)

### RESULT
Thus, The Python program to create a tuple containing all multiples of 5 up to a given number **N** was implemented and executed successfully.
