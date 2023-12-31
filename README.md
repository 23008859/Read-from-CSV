# Read-from-CSV

## AIM:
TO write a python program for reading content from the csv file
## ALGORITHM:
### Step 1:
create a spreadsheet with any details in it with extension.csv
### Step 2:
open google colab and mount the drive for using the created file in the colab
### Step 3:
import pandas package as pdf for reading the csvfile using pd.read_csv(file.name)                              
### Step 4:
Use the function called head() and tail()
### Step 5:
End the program
## PROGRAM:
import pandas as pd
f=pd.read_csv('cars(1).csv')
print(f.head(10))
print(f.tail())
print("rows",lens(f.axex[0]))
print(columns",len(f.axes[1])

## OUTPUT:
![Screenshot 2023-12-31 114103](https://github.com/23008859/Read-from-CSV/assets/139117979/6b6793b3-c467-4520-84ea-70a8d3d0e60a)

## RESULT: 
Thus the pyhton program for reading content from csv file is sucessful
