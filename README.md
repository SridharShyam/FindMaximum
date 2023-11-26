# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: SHYAM S
RegisterNumber: 23012478 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: SHYAM S
RegisterNumber: 23012478
'''
def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    maxi=list1[0]
    for i in list1:
        if(i>maxi):
            maxi=i
    return maxi

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![image](https://github.com/SridharShyam/FindMaximum/assets/144871368/2337d812-6577-412b-a78a-d2b978c9f22e)
![image](https://github.com/SridharShyam/FindMaximum/assets/144871368/da11f03f-ecd3-495d-b14b-86ff4145f3c2)
![image](https://github.com/SridharShyam/FindMaximum/assets/144871368/bd334f16-01fd-433b-9f1f-ecc647a37797)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
