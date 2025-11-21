# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
## Developed By : VIMALRAJ B
## Register Number : 212224230304
```
import numpy as np

x = np.array(eval(input()))
y = np.array(eval(input()))


greater_positions = np.where(x > y)
print(greater_positions)

equal_positions = np.where(x == y)
print(equal_positions)
```
## Output



<img width="1105" height="317" alt="image" src="https://github.com/user-attachments/assets/f2db29c6-3d9f-49ec-bcf5-5bd33aee9757" />



## Result

Thus , the program was executed Successfully.
