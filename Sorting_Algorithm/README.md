# Sorting Algorithms

These videos will help you visualise these algorithms better.

[**Quick Sort**](https://www.youtube.com/watch?v=aXXWXz5rF64)

[**Merge Sort**](https://www.youtube.com/watch?v=es2T6KY45cA)

*Quick sort* works faster than other sorting algorithms for small data sets, while *Merge sort* has a consistent speed on any size of data.
Check out more differences [here](https://www.geeksforgeeks.org/quick-sort-vs-merge-sort/)

### Example Videos:
Look at these videos to learn how same things can be done to sort number arrays: 
- [Merge Sort](https://www.youtube.com/watch?v=JSceec-wEyw)
- [Quick Sort](https://www.youtube.com/watch?v=PgBzjlCcFvc)

## Dive Deep:
Try writing code for sorting an array using both Quick sort and Merge sort algorithms. [Recursion](https://www.geeksforgeeks.org/recursion/) is the key to both.     
* **Quick Sort:** QuickSort is a Divide and Conquer algorithm. It picks an element as pivot and partitions the given array around the picked pivot. There are many different versions of quickSort that pick pivot in different ways.

  -  Always pick first element as pivot.
  -  Always pick last element as pivot (implemented below)
  -  Pick a random element as pivot.
  -  Pick median as pivot.
  
The key process in quickSort is partition(). Target of partitions is, given an array and an element x of array as pivot, put x at its correct position in sorted array and put all smaller elements (smaller than x) before x, and put all greater elements (greater than x) after x. All this should be done in linear time.
Check [code](https://www.geeksforgeeks.org/quick-sort/) for more help.     

* **Merge Sort:** Like QuickSort, Merge Sort is also Divide and Conquer algorithm. It divides input array in two halves, calls itself for the two halves and then merges the two sorted halves. The merge() function is used for merging two halves. The merge(arr, l, m, r) is key process that assumes that arr[l..m] and arr[m+1..r] are sorted and merges the two sorted sub-arrays into one.
Check [code](https://www.geeksforgeeks.org/quick-sort/) for more help.
