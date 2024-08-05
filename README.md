# Merge Sort Algorithm
**Introduction**

Merge Sort is a divide-and-conquer algorithm that divides the input array into two halves, recursively sorts both halves, and then merges the sorted halves to produce a sorted array. It is an efficient, stable, and comparison-based sorting algorithm.

**Time Complexity**
* Best Case: O(n log n)
* Average Case: O(n log n)
* Worst Case: O(n log n)
Here, n is the number of elements in the list.

**Explanation**

1) Merge Function:

* Parameters: array, left, mid, right
* Divides the array into two subarrays: leftArray and rightArray.
* Merges the two subarrays into the original array in sorted order.

2) Merge Sort Function:

* Parameters: array, begin, end
* Recursively divides the array into halves until the base case (single element or empty array) is reached.
* Calls the merge function to merge the divided arrays.

3) Print Array Function:

* Parameters: array, size
* Prints the elements of the array.

4) Main Execution:

* Initializes an array arr with unsorted elements.
* Prints the given array before sorting.
* Calls the mergeSort function to sort the array.
* Prints the sorted array.

**Usage**

* Run the code.
* The program will output the original array before sorting and the sorted array after applying merge sort.
