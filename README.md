# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the Program
### Step 2: 
Get the input from the user using the eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Use concatenation operation display the entire related list
### Step 6: 
Stop the Program
## Program:
```
#Program to circulate N values.
#Developed by: yashvanth k
#RegisterNumber:23011613
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![Exp 1 b](https://github.com/Yashvanth21/Circulate-the-values-of-N-variables/assets/144979957/799d8e2a-b931-4b45-a8ba-fce5cfe7c4ab)

## Result:
The python program for Circulate of N variables program executed successfully.
