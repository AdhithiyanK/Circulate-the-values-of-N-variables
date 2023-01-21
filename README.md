# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Commence the program
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the rotated list
### Step 6: 
End the program
## Program:
~~~
#Program to circulate N values.
#Developed by: Adhithiyan K
#RegisterNumber: 22001999
def circulate():
    n=int(input())
    l=[10,20,30,40,50,60]
    a=l[n:]+l[:n]
    print("After circulating the values are:",a)
~~~
## Output:
![image](https://user-images.githubusercontent.com/121029258/213874453-25d1607f-1631-41bf-9d61-eabe5b5c9d71.png)
## Result:
The variables are rotated successfully.
