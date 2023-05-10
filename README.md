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
```
program to mark the maximum of marks using the method sort.
Developed by: yogesh rao S D
Registernumber: 212222110055
```
def max_marks(marks):
    a=sorted(marks)
    b=a[-1]
    return b



```

ii)	# To find the maximum marks using the list method max().
```
program to mark maximum marks using the list method max().
Developed by: yogesh rao S D
Registernumber: 212222110055
```
def max_marks(marks):
    a=max(marks)
    return a



```

iii) # To find the maximum marks without using builtin functions.
```
program to the maximum marks without using builtin functions.
Developed by: yogesh rao S D
Registernumber: 212222110055
```
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max 
    
    
```


## Output:
```
 i) # To find the maximum of marks using the list method sort.
 
 ![image](https://github.com/yogeshrao05/FindMaximum/assets/122008288/12885119-cc26-4d56-b744-c05fafa74494)


 ii)	# To find the maximum marks using the list method max().
 
 
 ![image](https://github.com/yogeshrao05/FindMaximum/assets/122008288/d5851a5d-c593-42f0-8875-3562dacc7d18)
 
 
 iii) # To find the maximum marks without using builtin functions.
 
 
 ![image](https://github.com/yogeshrao05/FindMaximum/assets/122008288/e26dfd00-adbf-4ecd-9cbc-8b2306d65b2e)



```
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
