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
```
import pandas as pd
d=pd.DataFrame({'s_id':['S1','S2','S3','S4','S5'],'name':['Dan','Ryder','Bryce','Bernal','Kwame'],'marks':[200, 210, 190, 222,199]})
f=pd.DataFrame({'s_id':['S4','S5','S6','S7','S8'],'name':['Scart','Willy','Dani','Kaise','Madeeha'],'marks':[201,200,198,219,201]}
)
print(d)
print(f)
print(pd.concat([d,f]))
```

## Output

<img width="393" height="518" alt="image" src="https://github.com/user-attachments/assets/f4cbfb03-b33e-45ab-8ab2-5da7a3531f61" />


## Result
Thus,the program has been executed successfully
