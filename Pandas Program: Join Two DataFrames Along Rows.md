# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```python
import pandas as pd

# Create First DataFrame
student_data1 = {
    'Name': ['Arun', 'Bala', 'Charan'],
    'Marks': [85, 90, 78]
}

df1 = pd.DataFrame(student_data1)

# Create Second DataFrame
student_data2 = {
    'Name': ['Deepak', 'Esha', 'Farhan'],
    'Marks': [88, 92, 80]
}

df2 = pd.DataFrame(student_data2)

# Condition: Check if both DataFrames have the same columns
if list(df1.columns) == list(df2.columns):
    result = pd.concat([df1, df2], axis=0)
    print("Concatenated DataFrame:")
    print(result)
else:
    print("Cannot concatenate. Column names are different.")
```
## Output
<img width="287" height="214" alt="{864AEABA-444E-4CF5-B0D1-0C2F4C0FC215}" src="https://github.com/user-attachments/assets/f46b8516-320b-42fa-ae97-8d78908d4e50" />

## Result
The code was successfully executed by using python
