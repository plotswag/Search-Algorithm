# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
``` 
Program to mark the maximum of marks using the list method sort
Developed by: jeevanesh
RegisterNumber: 23013802
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```
ii)	# Find the element in a list using Binary Search(Iterative Method).
``` 
Program to find the maximum marks using the list method max().
Developed by: jeevanesh
RegisterNumber: 23013802
'''
def max_marks(marks):
    max_value=max(marks)
    return max_value    
```
iii)	# Find the element in a list using Binary Search (recursive Method).
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: jeevanesh
RegisterNumber: 23013802
'''
def max_marks(list1):
    max= list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        
```
## Sample Input and Output
![image](https://github.com/plotswag/Search-Algorithm/assets/145822344/62da807d-6cb3-4ba8-998b-2349360e4a73)
![image](https://github.com/plotswag/Search-Algorithm/assets/145822344/410f9779-861e-407c-ba3a-80d4a3e62aba)
![image](https://github.com/plotswag/Search-Algorithm/assets/145822344/8b4e0c4a-8317-4550-95c0-fe74742813a3)

## Result
Thus the linear search and binary search algorithm is implemented using python programming.
