# DATE: 
# EX.NO.02 Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept

## Equipment’s required:
PC
Anaconda - Python 3.7

## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
print the result

## Program:
```python
program to Circulate the n variables using function concept
DEVELOPED BY: MOHAN.S
REGISTER NO: 212223240094

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print('After circulating the values are:',l)
```


## Output:

![alt text](<Screenshot 2024-08-25 185846.png>)


## Result:
The output for circulate the values of n variables is successfull.
