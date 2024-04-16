# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
# Developed By : Murali Krishna S
# Register Number : 212223230129

num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if num[j]<num[low]:
            low=j
    num[i],num[low]=num[low],num[i]
print(num)    
        





```
ii)	#Insertion Sort
```
# Developed By : Murali Krishna S
# Register Number : 212223230129

num=eval(input())
for i in range(1,len(num)):
    insert = num[i]
    j=i-1
    while j>=0 and num[j]>=insert:
        num[j+1]=num[j]
        j=j-1
    num[j+1]=insert
print(num)    





```

## Output:
![image](https://github.com/Murali-Krishna0/Sorting-Algorithms/assets/149054535/a2a822e4-9399-464d-b19f-4029b986d7b4)
![image](https://github.com/Murali-Krishna0/Sorting-Algorithms/assets/149054535/b7e733b8-5366-4a51-80e0-aae6df3b987c)
![image](https://github.com/Murali-Krishna0/Sorting-Algorithms/assets/149054535/7d70bc2e-e0c0-4dea-83aa-c3e67907bb6f)
![image](https://github.com/Murali-Krishna0/Sorting-Algorithms/assets/149054535/aafcdc23-a63b-4d8f-9983-08abaa857982)



## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
