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
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: L.yagnesh kumar reddy
RegisterNumber: 23004742
'''
def insertion_sort(nums):
    for i in range(1, len(nums)):
        item_to_insert = nums[i]
        j = i-1
        while j >= 0 and nums[j] > item_to_insert:
            nums[j+1] = nums[j]
            j -= 1
        nums[j+1] = item_to_insert
list_of_nums = eval(input())
insertion_sort(list_of_nums)
print(list_of_nums)
```
ii)	#Insertion Sort
```
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: L.yagnesh kumar reddy
RegisterNumber: 23004742
'''
def insertion_sort(nums):
    for i in range(1, len(nums)):
        item_to_insert = nums[i]
        j = i-1
        while j >= 0 and nums[j] > item_to_insert:
            nums[j+1] = nums[j]
            j -= 1
        nums[j+1] = item_to_insert
list_of_nums = eval(input())
insertion_sort(list_of_nums)
print(list_of_nums)
```

## Output:
![image](https://github.com/23004742/Sorting-Algorithm/assets/150319318/195926dc-d1fa-4304-ba8e-d83ade4f5468)
![image](https://github.com/23004742/Sorting-Algorithm/assets/150319318/63fae446-9a58-4349-bf93-0ac71557a774)


## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
