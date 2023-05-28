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
def max_marks(marks):
    #return max(marks)
    marks.sort()
    large= marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    # write your code here
    max= list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
    
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/Sanjay-sg/FindMaximum/assets/119559022/9f07b08e-603b-427f-ae19-65ecfc6872a2)
![image](https://github.com/Sanjay-sg/FindMaximum/assets/119559022/b5ee9420-eb1c-457a-8302-8fc7074e974e)
![image](https://github.com/Sanjay-sg/FindMaximum/assets/119559022/99968cd7-fb95-4b56-8839-4f92b0e4838b)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
