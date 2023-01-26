# Read-from-CSV

## AIM:

To write a python program for reading the csv file content.

## EQUIPMENTS REQUIRED:

PC Anaconda - Python 3.7


## ALGORITHM:

### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.


## PROGRAM:
```

'''
Developed By :  P Sri Varshan

Referance No. : 22008051
'''
import pandas as pd
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))

```

## OUTPUT:

![6 Sri](https://user-images.githubusercontent.com/114944059/214782342-1b2af010-fa42-461d-841d-512361a284d5.png)



## RESULT:

Thus a python program is written to read the contents of a CSV file.
