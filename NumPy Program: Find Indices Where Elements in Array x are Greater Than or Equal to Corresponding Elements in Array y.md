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
```python
import numpy as np

# Create two arrays
x = np.array([10, 20, 30, 40, 50])
y = np.array([15, 18, 30, 35, 60])

# Find indices where x >= y
indices = np.where(x >= y)

print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices[0])
```
## Output
<img width="368" height="140" alt="Screenshot 2026-05-31 153405" src="https://github.com/user-attachments/assets/b50f0d5d-8e93-4251-9d29-11c30f320ca4" />


## Result
The code was successfully executed by using python
