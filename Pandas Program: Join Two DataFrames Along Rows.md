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
```import pandas as pd
df1 = pd.DataFrame({
    's_id': ['S1', 'S2', 'S3', 'S4', 'S5'],
    'name': ['Fenton', 'Ryder', 'Bryce', 'Bernal', 'Morin'],
    'marks': [200, 210, 190, 222, 199]
})

df2 = pd.DataFrame({
    's_id': ['S4', 'S5', 'S6', 'S7', 'S8'],
    'name': ['Scarlette', 'Carla', 'Dante', 'Kaiser', 'Madeeha'],
    'marks': [201, 200, 198, 219, 201]
})
result_data = pd.concat([df1, df2],axis=0)
print(result_data)
```

## Output
<img width="1206" height="552" alt="image" src="https://github.com/user-attachments/assets/7a9d13ac-bd78-4985-972e-73269559f886" />

## Result
Thus the program to write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame is verified successfully.

