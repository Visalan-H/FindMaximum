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
![image](https://github.com/Visalan-H/FindMaximum/assets/152077751/4a68897d-1d5e-477c-994a-666d74b5fa32)

![image](https://github.com/Visalan-H/FindMaximum/assets/152077751/30334da7-7232-4b6c-9ee6-64afb3723cd0)

![image](https://github.com/Visalan-H/FindMaximum/assets/152077751/c7a97df3-6026-4441-b176-f1c52768bee4)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
