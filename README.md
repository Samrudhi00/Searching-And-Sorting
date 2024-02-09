# Searching-And-Sorting
Codebase for efficient searching and sorting algorithms leaning


**SEARCH ALGORITHMS**


**Linear Search Algorithm**
Linear Search is defined as a sequential search algorithm that starts at one end and goes through each element of a list until the desired element is found, otherwise the search continues till the end of the data set.
TC = O(n)  SC =(1) no requirement of additional memory

When to use Linear Search?
When we are dealing with a small dataset.
When you are searching for a dataset stored in contiguous memory.



**Binary Search**
Binary Search is defined as a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(log N). 


**Iterative Binary Search Algorithm**
Here we use a while loop to continue the process of comparing the key and splitting the search space in two halves.
TC: O(log N) SC: O(1)


**Recursive Binary Search Algorithm**
Create a recursive function and compare the mid of the search space with the key. And based on the result either return the index where the key is found or call the recursive function for the next search space.
TC:O(log N)
SC :O(1), If the recursive call stack is considered then the auxiliary space will be O(logN).




**SORTING ALGORITHMS**
A Sorting Algorithm is used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure.


**Selection Sort**
Selection sort is a simple and efficient sorting algorithm that works by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion of the list. 

SMALL,MID,LARGE POINTERS mid=(small+large)/2
TC:O(n^2)  SC : O(1)
temporary space is used for swapping 



**Bubble Sort**
Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in the wrong order.in every round we place largest element at last position
TC:O(N2) SC: O(1)


**Insertion Sort**
Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part.
TC: O(N^2) SC: O(1)


**Merge Sort**
Merge sort is defined as a sorting algorithm that works by dividing an array into smaller subarrays, sorting each subarray, and then merging the sorted subarrays back together to form the final sorted array.
Merge sort is a recursive algorithm that continuously splits the array in half until it cannot be further divided i.e., the array has only one element left (an array with one element is always sorted). Then the sorted subarrays are merged into one sorted array.
TC:
SC:


**Quick Sort**


**Heap Sort**


**Counting Sort**
**Even Odd Sort**
**Radix Sort**
**Merge Sort**


