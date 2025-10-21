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
```
import numpy as np
a=np.array(eval(input()))
print("Given array")
print("",a)
print()
print(np.sort(a,axis=0))
```
## Output
<img width="792" height="557" alt="image" src="https://github.com/user-attachments/assets/6d5997e7-dcd3-4f15-b4df-ad70f6223ae8" />

## Result
Thus the program to write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is verified successfully.
