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
Developed by:AJITH KUMAR A 
RegisterNumber: 23002150
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python 
''' 
Program to find the maximum marks using the list method max().
Developed by: AJITH KUMAR A
RegisterNumber: 23002150
'''
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: AJITH KUMAR A
RegisterNumber: 23002150
'''
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large


```
## Sample Input and Output
i)![image](https://github.com/Ajith1413/FindMaximum/assets/139842524/26ea0622-4665-4ba7-b288-7ab77e71cdaa)

ii)![image](https://github.com/Ajith1413/FindMaximum/assets/139842524/ee380cca-3873-4da0-af2d-34d092ce4c32)

iii)![image](https://github.com/Ajith1413/FindMaximum/assets/139842524/29f51b72-4a48-4868-a1ae-f45b235fb78d)

## Output:

![output](./img/max_marks1.jpg) 
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Ajith1413/FindMaximum/assets/139842524/9956a73d-9772-44c7-a1b4-613b69ca2927)


ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Ajith1413/FindMaximum/assets/139842524/2a029036-df88-496e-95a7-0e738adf9d7b)


iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Ajith1413/FindMaximum/assets/139842524/98c2a8fe-ba17-48d2-acde-28f35ace4745)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
