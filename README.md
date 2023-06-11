# Read-from-CSV

## AIM:

To write a python program for reading content from a CSV file

## ALGORITHM:

Step 1:Import pandas as pd.

Step 2:Read the CSV file using read_csv method.

Step 3:Use head and tail method to get the required contents from the file.

Step 4:Use len() method to get the number of rows and colu

Step 5:Print the output

## PROGRAM:
```
Developed by: PREM KUMAR K
Register number:212222230111

import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no.of.rows",len(df.axes[0]))
print("no.of.columns",len(df.axes[1]))  
```

## OUTPUT:
![image](https://github.com/premkumarkarthikeyan/Read-from-CSV/assets/119476243/581fbc0f-601a-4484-bd37-9fdd3540b80f)
## RESULT:

Thus a python program is written to read the contents of a CSV file.
