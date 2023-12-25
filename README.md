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
i)![Screenshot 2023-11-29 141129](https://github.com/Ajith1413/FindMaximum/assets/139842524/fc7bcc96-24fc-4f52-9355-99d81880b1d7)

ii)![Screenshot 2023-11-29 141348](https://github.com/Ajith1413/FindMaximum/assets/139842524/b158d3b4-6fe8-432a-8cd6-feb2c589908a)


iii)![Screenshot 2023-11-29 141622](https://github.com/Ajith1413/FindMaximum/assets/139842524/5c601ffe-3fb9-4965-9dde-6a2deddf608f)


## Output:
![Screenshot 2023-11-29 140952](https://github.com/Ajith1413/FindMaximum/assets/139842524/ffa72f50-4769-40ea-94b5-b16add15cecb)

![Screenshot 2023-11-29 141404](https://github.com/Ajith1413/FindMaximum/assets/139842524/6949c1df-7aeb-4643-a7e9-ed454e13b5b1)

![Screenshot 2023-11-29 141646](https://github.com/Ajith1413/FindMaximum/assets/139842524/7856675e-6809-4e75-887a-d416325fbfc8)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
