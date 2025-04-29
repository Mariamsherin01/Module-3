# Exp.No:3a
## STRING - Capitalizing Every Other Letter in a String

---

### AIM  
To write a Python function that reads a string and returns a new string with every other letter capitalized, starting from the second letter (index 1).

---

### ALGORITHM

1.Define a function convert that accepts a string as input.

2.Initialize an empty result string.

3.Loop through each character using its index in the input string.

4.If the index is even, add the lowercase character to the result.

5.If the index is odd, add the uppercase character to the result.

6.Print the resulting string after the loop.
---

### PROGRAM

```
reg.no: 212222060143
name: Mariam Sherin
def convert(input_str):
    output_str = ""
    for i, char in enumerate(input_str):
        if i % 2 == 0:
            output_str += char.lower()
        else:
            output_str += char.upper()
    print(output_str)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/1f2da933-7943-445a-989e-de98c6910dd3)

### RESULT
Thus, The Python function that reads a string and returns a new string with every other letter capitalized, starting from the second letter was implement and executed successfully.
