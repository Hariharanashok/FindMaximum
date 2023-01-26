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
#Program to mark the maximum of marks using the list method sort
#Developed by: HARIHARAN A
#RegisterNumber: 22001891
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large
    
```

ii)	# To find the maximum marks using the list method max().
```Python
#Program to find the maximum marks using the list method max().
#Developed by: HARIHARAN A
#RegisterNumber: 22001891
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program to the maximum marks without using builtin functions.
#Developed by: HARIHARAN A
#RegisterNumber: 22001891
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```
## Sample Input and Output
![image](https://user-images.githubusercontent.com/120353431/214831696-25c042b3-3f2b-450d-b220-9d3186510d8a.png)
![image](https://user-images.githubusercontent.com/120353431/214831794-61c1a78e-c75d-4dd1-b121-569c3e42d898.png)
![image](https://user-images.githubusercontent.com/120353431/214831953-261f38f5-e3f6-44dd-a0d6-93e08aab4075.png)


## Output:
![image](https://user-images.githubusercontent.com/120353431/214830975-b15bcc24-dd1f-4bbd-9319-ea98836defbd.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
