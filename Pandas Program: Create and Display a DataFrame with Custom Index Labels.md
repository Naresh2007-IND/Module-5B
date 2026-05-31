# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```python
import pandas as pd

# Create Dictionary
exam_data = {
    'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily'],
    'score': [12.5, 9, 16.5, 15, 9],
    'attempts': [1, 3, 2, 3, 2],
    'qualify': ['yes', 'no', 'yes', 'yes', 'no']
}

# Index Labels
labels = ['a', 'b', 'c', 'd', 'e']

# Create DataFrame
df = pd.DataFrame(exam_data, index=labels)

# Display DataFrame
print(df)
```


## Output
<img width="384" height="177" alt="Screenshot 2026-05-31 153913" src="https://github.com/user-attachments/assets/8985634b-4074-4228-872f-616366dd90a8" />

## Result
The code was successfully executed by using python
