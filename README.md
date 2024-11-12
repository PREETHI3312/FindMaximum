# DATE:
# EXP-6: Find the maximum of a list of numbers
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

DEVELOPED BY:A K PREETHI
REGISTER NUMBER:212223230156

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
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark

```



## Output:
# To find the maximum of marks using the list method sort.
![image](https://github.com/user-attachments/assets/3f2a0660-cedd-4bf1-8904-8ed1d8db8922)

# To find the maximum marks using the list method max().
![image](https://github.com/user-attachments/assets/071f2f4e-2dfa-4c8a-9863-27faa6a6e35b)

 # To find the maximum marks without using builtin functions.
 ![image](https://github.com/user-attachments/assets/8e071646-00fc-4b70-9f30-6f6cee7a9d88)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
