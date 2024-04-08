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
Developed by:Visalan H
Register Number:212223240183
i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort(reverse=True)
    return marks[0]
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    max=marks[0]
    for i in marks:
        if(i>max):
            max=i
    return max        
```

## Output:
Sort():
![alt text](image.png)

Inbuilt Max():
![alt text](image-1.png)

User-defined Max():
![alt text](image-2.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
