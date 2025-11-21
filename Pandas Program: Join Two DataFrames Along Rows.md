# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

## 💻 Program
## Developed By : VIMALRAJ B
## Register Number : 212224230304
```
import pandas as pd
d1=pd.DataFrame(eval(input()))
d2=pd.DataFrame(eval(input()))
ex=pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(d1)
print(d2)
print(ex)
print("\nJoin first two said dataframes along rows:")
result=pd.concat([d1,d2],axis=0)
print(result)
print("\nNow join the said result_data and df_exam_data along student_id:")
fin=pd.merge(result,ex,on='s_id')
print(fin)
```
## Output

<img width="1535" height="892" alt="image" src="https://github.com/user-attachments/assets/f46f6bec-9dd7-4369-abfd-12b837212f20" />


## Result

Thus , the program was executed Successfully.
