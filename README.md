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
