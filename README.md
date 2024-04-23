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
# Program to mark the maximum of marks using the list method sort.
# Developed by: GANESH G.
# Register No:212223230059
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
# Program to find the maximum marks using the list method max().
# Developed by: GANESH G.
# Register No: 212223230059
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
# Program to find the maximum marks without using builtin functions.
# Developed by: GANESH G.
# Register No: 212223230059
def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark
```



## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/ganesh10082006/FindMaximum/assets/151981672/5f93be4c-6588-4a0e-b600-aca37f127e6f)
ii) # To find the maximum marks using the list method max().
![image](https://github.com/ganesh10082006/FindMaximum/assets/151981672/ca3ef30b-e00a-4b9f-90b4-36603d5c68f0)
iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/ganesh10082006/FindMaximum/assets/151981672/d83d2880-7de1-4e0f-a158-4f0e05c9c951)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
