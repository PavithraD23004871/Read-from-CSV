# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result
## PROGRAM:
Developed by:pavithra.D
Register No: 212223230146

To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
## OUTPUT:
![WhatsApp Image 2023-12-27 at 19 00 28_4e5b71d9](https://github.com/PavithraD23004871/Read-from-CSV/assets/138955967/cdafe2cb-d7b8-4867-be96-9af22152ddbb)

## RESULT:
