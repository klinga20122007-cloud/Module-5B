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
```
import pandas as pd
import numpy as np
exam_data = {
    'name': ['Alice', 'Bob', 'Charlie', 'David', 'Eva'],
    'score': [85, 62, 77, 90, 58],
    'attempts': [1, 3, 2, 1, 4],
    'qualify': ['yes', 'no', 'yes', 'yes', 'no']
}
labels = ['a', 'b', 'c', 'd', 'e']
df = pd.DataFrame(exam_data, index=labels)
print("DataFrame:")
print(df)
```

## Output
<img width="1462" height="477" alt="image" src="https://github.com/user-attachments/assets/d5fb9737-279a-4fd2-bbb6-a01698018061" />

## Result
Thus the program to create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows is verified successfully.
