# Sorting



##  Aim
To study and implement different sorting methods in C++.

---

##  Theory

Sorting in C++ involves arranging elements within a data structure, such as an array or vector, in a specific order (e.g., ascending or descending).  
C++ provides various methods for sorting, including built-in functions and custom implementations of sorting algorithms.

---

###  Selection Sort
Selection Sort is a comparison-based sorting algorithm. It sorts an array by repeatedly selecting the smallest (or largest) element from the unsorted portion and swapping it with the first unsorted element.


---

###  Bubble Sort
Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping adjacent elements if they are in the wrong order.

**Working:**
1. After the first pass, the largest element moves to the last position.  
2. After the second pass, the second largest element moves to the second last position.  
3. Continue until all elements are sorted.  

---

###  Insertion Sort
Insertion Sort works by iteratively inserting each element into its correct position in a sorted portion of the list.  
It is similar to sorting playing cards in your hands.

**Working:**
1. Start with the second element (first is considered sorted).  
2. Compare it with previous elements and insert it in the correct position.  
3. Repeat for all elements until the array is sorted.  

##  Algorithms

###  Selection Sort
Start
Input n (size of array)
Input n elements into the array
For i = 0 to n-2:
Set minIndex = i
For j = i+1 to n-1:
If arr[j] < arr[minIndex], update minIndex = j
Swap arr[i] and arr[minIndex]
Display the sorted array
End


###  Insertion Sort
Start
Input n (size of array)
Input n elements into the array
For i = 1 to n-1:
Set key = arr[i]
Set j = i - 1
While j >= 0 and arr[j] > key:
Shift arr[j] to arr[j+1]
Decrement j
Place key at arr[j+1]
Display the sorted array
End


###  Bubble Sort
Start
Input n (size of array)
Input n elements into the array
For i = 0 to n-2:
Set swapped = false
For j = 0 to n-i-2:
If arr[j] > arr[j+1]:
Swap arr[j] and arr[j+1]
Set swapped = true
If swapped = false, break (array already sorted)
Display the sorted array
End


##  Conclusion
We learnt to implement **Selection Sort, Bubble Sort, and Insertion Sort** in C++.  
These algorithms are useful for understanding the fundamentals of sorting and time
