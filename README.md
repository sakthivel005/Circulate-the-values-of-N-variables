# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Get the values from the user

### Step 2: 
Assign values in a variable

### Step 3: 
Get the value from the user for the number of rotation

### Step 4: 
Using the slicing concept rotate the list

### Step 5:
By using concatenation operator,it will join the two values

### Step 6: 
print the output

## Program:
```
#Program to circulate N values.
#Developed by:sakthivel R
#RegisterNumber:22009121
def circulate():
   l=eval(input())
   n=int(input())
   l=l[n:]+l[:n]
   print("After circulating the values are:",l)
 ```
  
## Output:
![Screenshot from 2022-12-26 12-58-08](https://user-images.githubusercontent.com/120550359/209518231-7e5f2aac-b04c-4032-92a2-ddd834db13e0.png)

## Result:
circulate the n variables using function is successfully executed
