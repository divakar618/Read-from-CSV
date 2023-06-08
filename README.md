# Read-from-CSV

## AIM:

To write a program for reading the csv file content.

## ALGORITHM:
### Step 1:

Load the CSV into a DataFrame

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of row returned is defined in pandas option settings.

### Step 4:
Check your systems maximun column with the pd.options.display.max_columun statement

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.



## PROGRAM:
```
developed by: DIVAKAR R
register number: 212222240026

import pandas as pd df = pd.read_csv('nba.csv') 
print(df.head(10)) print(df.tail()) print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
```


## OUTPUT:



![243408700-39fae374-bc0e-45c3-ab7e-b36b6cd6a55d](https://github.com/divakar618/Read-from-CSV/assets/121932143/66ef8de1-aa5d-452e-8828-4470ebbf4534)




## RESULT:

Thus the program written to read csv file.


