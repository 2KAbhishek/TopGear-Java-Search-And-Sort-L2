# Training Tasks

1. Task to implement binary search using Recursive Algorithm :
   A binary search or half-interval search algorithm finds the position of a specified value (the input "key") within a
   sorted array. In each step, the algorithm compares the input key value with the key value of the middle element of the
   array. If the keys match, then a matching element has been found so its index, or position, is returned. Otherwise, if
   the sought key is less than the middle element's key, then the algorithm repeats its action on the sub-array to the left
   of the middle element or, if the input key is greater, on the sub-array to the right. If the remaining array to be searched
   is reduced to zero, then the key cannot be found in the array and a special "Not found" indication is returned.
   Every iteration eliminates half of the remaining possibilities. This makes binary searches very efficient - even for large
   collections. Binary search requires a sorted collection. Also, binary searching can only be applied to a collection that
   allows random access (indexing).

   Worst case performance: O(log n)
   Best case performance: O(1)

   Recursion is used in this algorithm because with each pass a new array is created by cutting the old one in half. The
   binary search procedure is then called recursively, this time on the new array. Typically the array's size is adjusted by
   manipulating a beginning and ending index. The algorithm exhibits a logarithmic order of growth because it essentially
   divides the problem domain in half with each pass.

2. Task to implement merge sort in Java:
   Merge sort is a divide and conquer algorithm.
   Steps to implement Merge Sort:

   Divide the unsorted array into n partitions, each partition contains 1 element. Here the one element is considered as sorted.

   Repeatedly merge partitioned units to produce new sub-lists until there is only one sub list remaining. This will be the sorted list at the end.

   Merge sort is a fast, stable sorting routine with guaranteed O(n\*log(n)) efficiency. When sorting arrays, merge sort
   requires additional scratch space proportional to the size of the input array. Merge sort is relatively simple to code
   and offers performance typically only slightly below that of quicksort.

3. Task to implement bubble sort in Java:

   Bubble sort, also referred to as sinking sort, is a simple sorting algorithm that works by repeatedly stepping through
   the list to be sorted, comparing each pair of adjacent items and swapping them if they are in the wrong order. The
   pass through the list is repeated until no swaps are needed, which indicates that the list is sorted. The algorithm gets
   its name from the way smaller elements "bubble" to the top of the list. Because it only uses comparisons to operate
   on elements, it is a comparison sort. Although the algorithm is simple, most of the other sorting algorithms are more
   efficient for large lists.

   Bubble sort has worst-case and average complexity both О(n2), where n is the number of items being sorted. There
   exist many sorting algorithms with substantially better worst-case or average complexity of O(n log n). Even other
   О(n2) sorting algorithms, such as insertion sort, tend to have better performance than bubble sort. Therefore, bubble
   sort is not a practical sorting algorithm when n is large. Performance of bubble sort over an already-sorted list (bestcase) is O(n).
