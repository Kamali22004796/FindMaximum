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
Developed by: kamali.E
RegisterNumber: 22004796
'''
def max_marks(list1):
    temp=0
    for i in list1:
        if temp<i:
            temp=i
    return temp


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: kamali.e 
RegisterNumber: 22004796
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: kamali.e
RegisterNumber: 22004796
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![output](./img/max_marks2.jpg)

## Output:
i)	# To find the maximum of marks using the list method sort.
![](Screenshot%20from%202023-01-26%2014-09-17.png)

ii)	# To find the maximum marks using the list method max().
![](Screenshot%20from%202023-01-26%2014-09-48.png)

iii) # To find the maximum marks without using builtin functions.
![](Screenshot%20from%202023-01-26%2014-10-16.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.