# Read-from-CSV

## AIM:
To write a python program for reading the csv file content.

## ALGORITHM:
### Step 1:Import pandas library using import statement.
### Step 2:
### Step 3:The number of rows returned is defined in Pandas option settings.
### Step 4:Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
##Developed by: Evangelin.S
##REGISTER NUMBER: 212221230025
import pandas as pd
df= pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))
## OUTPUT:

## RESULT:
