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
![Screenshot 2024-03-24 202246](https://github.com/pavithraselvaraj30/FindMaximum/assets/149366880/26b497ab-c6a6-40c6-833c-d70700c26c4b)

![Screenshot 2024-03-24 202304](https://github.com/pavithraselvaraj30/FindMaximum/assets/149366880/7e63f9af-bcac-47a2-b602-d4b074afa509)

![Screenshot 2024-03-24 202325](https://github.com/pavithraselvaraj30/FindMaximum/assets/149366880/daf4c691-3829-47e2-8495-68059c3ae11b)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
