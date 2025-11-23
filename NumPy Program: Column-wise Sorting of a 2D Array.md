#  EX 5a:NumPy Program: Column-wise Sorting of a 2D Array

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
arr=np.array(eval(input()))
print("Given array")
print(arr)
print()
print(np.sort(arr,axis=0))
```



## Output
<img width="1049" height="437" alt="Screenshot 2025-11-23 182346" src="https://github.com/user-attachments/assets/355a90b3-18be-4372-8f36-d9a785ebde55" />


## Result
The program executed successfully, sorting the elements of the array column-wise in ascending order. The original array and the sorted array were both displayed.
