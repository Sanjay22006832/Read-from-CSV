# Read-from-CSV

## AIM:
To read from nba.csv file and the print the result.

## ALGORITHM:
### Step 1:
Read the CSV file using read_csv method.
### Step 2:
Use head and tail method to get the required contents from the file.
### Step 3:
Use len() method to get the number of rows and columns.
### Step 4:
Print the output.
## PROGRAM:
```
Developed by:M Sanjay
Registration Number:212222240090
import pandas as pd
df=pd.read_csv("/content/nba (1).csv")
print(df.head(10))
print(df.tails())
print("rows",df.axes[0])
print("columms",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no. of columns",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2023-06-12 051159](https://github.com/Sanjay22006832/Read-from-CSV/assets/119830477/0e6a6606-ae36-4bc2-96e2-850ac34f8003)



## RESULT:
Thus,the experiment was executed successfully.
