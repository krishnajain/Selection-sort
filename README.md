# Selection-sort

SELECTION SORT is a comparison sorting algorithm that is used to sort a random list of items in ascending order. The comparison does not require a lot of extra space. It only requires one extra memory space for the temporal variable.
This is known as in-place sorting.



Solution (Algorithm)
Step 1) Get the value of n which is the total size of the array

Step 2) Partition the list into sorted and unsorted sections. The sorted section is initially empty while the unsorted section contains the entire list

Step 3) Pick the minimum value from the unpartitioned section and placed it into the sorted section.

Step 4) Repeat the process (n – 1) times until all of the elements in the list have been sorted.





Advantages of Selection Sort



The following are the advantages of the selection sort

It performs very well on small lists
It is an in-place algorithm. It does not require a lot of space for sorting. Only one extra space is required for holding the temporal variable.
It performs well on items that have already been sorted.








Disadvantages of Selection Sort



The following are the disadvantages of the selection sort.

It performs poorly when working on huge lists.
The number of iterations made during the sorting is n-squared, where n is the total number of elements in the list.
Other algorithms, such as quicksort, have better performance compared to the selection sort.
