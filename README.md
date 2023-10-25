# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
write your name and register name
### Step 2: 
define a function
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
give the print statement
### Step 6: 
execute the program
## Program:
```
#Program to circulate N values.
#Developed by:D.Nisha
#RegisterNumber:23012927
def circulate():
    n=eval(input())
    m=int(input())
    out=n[m:]+n[:m]
    print("After circulating the values are:",out)
```  


## Output:
![Alt text](<circulate n variables (2).png>)

## Result:
This program is successfully executed to circulte n variables.