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
Developed by: s.Roselin mary jovita
RegisterNumber:212222230122 
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
Developed by:S.Roselin mary jovita 
RegisterNumber: 212222230122
'''
def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:S.Roselin mary jovita 
RegisterNumber: 212222230122
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max= i
    return max
            
```
## Sample Input and Output



## Output:
![method sort](https://user-images.githubusercontent.com/119104296/235069911-8ef386b3-0591-4f8f-be16-6e5a21ed8330.png)


![method max](https://user-images.githubusercontent.com/119104296/235069947-dc405e11-ab50-4d37-802a-08373558aabe.png)

![built in function](https://user-images.githubusercontent.com/119104296/235070002-1876941d-3805-4df9-ae53-9cd38a09a3c7.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
