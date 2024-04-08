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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    maximum=marks[0]
    for i in marks:
        if(i>maximum):
            maximum=i
    return maximum

```



## Output:
![Screenshot 2024-04-08 161400](https://github.com/pavithraselvaraj30/FindMaximum/assets/149366880/9611a24d-17fb-4e93-a488-d3a893fc7196)

![Screenshot 2024-04-08 161414](https://github.com/pavithraselvaraj30/FindMaximum/assets/149366880/2390fcee-d7be-4e44-850f-64b915f8564b)

![Screenshot 2024-04-08 161431](https://github.com/pavithraselvaraj30/FindMaximum/assets/149366880/40a1894a-9c5e-4c0f-b330-5f4c8a18165c)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
