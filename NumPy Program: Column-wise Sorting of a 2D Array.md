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
d=np.array([[34,43,73],[82,22,12],[53,94,66]])
print("Printing Original array")
print(d)
s=d[:,d[1].argsort()]
print("Sorting Original array by second row")
print(s)
a=d[d[:,1].argsort()]
print("Sorting Original array by second column")
print(a)
```

## Output
<img width="453" height="272" alt="image" src="https://github.com/user-attachments/assets/333bdd1d-a987-4aad-9746-87a44e33bb49" />


## Result
Thus,the program has been successfully executed.
