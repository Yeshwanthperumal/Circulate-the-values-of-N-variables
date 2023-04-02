# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Assume the keyword to run the program
### Step 2:
Assinging the value for the first value
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
Using the slicing concept roate the list with the donate of the first variable
### Step 6:
Print the values for the first variable

## Program:
#Program to circulate N values.

#Developed by: Yeshwanth P

#RegisterNumber:212222230178

def circulate():

    list1=eval(input())
    
    n=int(input())
    
    result=list1[n:]+list1[:n]
    
    print("After circulating the values are:",result)
    
## Output:
![image](https://user-images.githubusercontent.com/119476088/229338888-78950128-59b1-49e6-addf-68e0cc6472f2.png)

## Result:
Thus the circulate the values of N variables for executed 
