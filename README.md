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
```''' 
Program to find the maximum marks using the list method max().
Developed by: Rajeshkannan.M
RegisterNumber: 21500434
'''
def max_marks(marks):
    max_mark=max(marks)
    return max_mark



```

ii)	# To find the maximum marks using the list method max().
```''' 
Program to find the maximum marks using the list method max().
Developed by: Rajeshkannan.M
RegisterNumber: 21500434
'''
def max_marks(marks):
    max_mark=max(marks)
    return max_mark



```

iii) # To find the maximum marks without using builtin functions.
```''' 
Program to the maximum marks without using builtin functions.
Developed by: Rajeshkannan.M
RegisterNumber: 21500434
'''
def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark



```
## Sample Input and Output
## Input
![output](./img/max_marks1.jpg) 

## Output:
![MAXMARKS1](https://user-images.githubusercontent.com/93901857/149080237-2178e829-fab5-4e6b-85d5-63eee2e3a825.jpg)
![MAXMARKS2](https://user-images.githubusercontent.com/93901857/149080245-5caf7b7c-53de-465d-8d73-9e552dfd2d84.jpg)
![MAXMARKS3](https://user-images.githubusercontent.com/93901857/149080251-91093477-3948-42cc-a8b1-15807bfa865d.jpg)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.