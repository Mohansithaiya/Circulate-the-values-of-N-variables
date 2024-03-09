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
def circulate():
    values=eval(input())
    n=int(input())
    for i in range(n):
        temp=values.pop(0)
        values.append(temp)
    print("After circulating the values are:",values)
```


## Output:
![Screenshot 2024-03-09 094343](https://github.com/Mohansithaiya/Circulate-the-values-of-N-variables/assets/154211682/ec14f956-d1dc-4978-a54e-58fad5ab1136)


## Result:
The output for circulate the values of n variables is successfull.
