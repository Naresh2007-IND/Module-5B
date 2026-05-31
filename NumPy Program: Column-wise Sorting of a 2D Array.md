# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```python
import numpy as np

# Create a 2D array
arr = np.array([[9, 3, 5],
                [4, 8, 1],
                [7, 2, 6]])

print("Original Array:")
print(arr)

# Sort each column
sorted_arr = np.sort(arr, axis=0)

print("\nColumn-wise Sorted Array:")
print(sorted_arr)
```
## Output
<img width="448" height="236" alt="Screenshot 2026-05-31 153226" src="https://github.com/user-attachments/assets/3d4ff98b-6e49-4d78-b29a-6e1b20877585" />

## Result
The code was successfully executed by the python
