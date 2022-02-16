# Read-from-CSV

## AIM:
To find read from CSV.
## ALGORITHM:
### Step 1:
load the csv into a data frame
### Step 2:
print the number of contents to be displayed using df.head()
### Step 3:
the number of rows returened is defined in pandas option settings
### Step 4:
check your systems maximum colum with the pd.options.display.max_colums statement
### Step 5:
increase the maximum number of rows to display the entire data frame

## PROGRAM:
'''Developed By Nme:S.Meena,Ref No:21500895
'''
```
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("No of rows",len(df.axes[0]))
print("No of columns",len(df.axes[1]))
```
## OUTPUT:
![jupiter](https://user-images.githubusercontent.com/94677128/153771490-dcfb6d23-098e-4878-93e8-ca959be41c4b.png)

## RESULT:
The program is run successfully.
