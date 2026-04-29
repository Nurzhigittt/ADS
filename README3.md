Assignment 3: Sorting and Searching Algorithm Analysis System

Project Overview

This project implements and compares three fundamental algorithms:

Bubble Sort (Basic Sorting)
Quick Sort (Advanced Sorting)
Binary Search (Searching)

The purpose of this experiment is to analyze algorithm performance using execution time and compare how different algorithms behave on various input sizes and data types (random vs sorted arrays).


Algorithm Descriptions

1. Bubble Sort

Bubble Sort is a simple comparison-based algorithm that repeatedly steps through the array, compares adjacent elements, and swaps them if they are in the wrong order.

Time Complexity:

   Best Case: O(n)
   Average Case: O(n²)
   Worst Case: O(n²)


2. Quick Sort
Quick Sort is a divide-and-conquer algorithm.
It selects a pivot element and partitions the array into two subarrays: elements smaller than the pivot and elements greater than the pivot.
The process is repeated recursively.

Time Complexity:

   Best Case: O(n log n)
   Average Case: O(n log n)
   Worst Case: O(n²)

3. Binary Search
Binary Search works by repeatedly dividing a sorted array in half to locate a target element.
Time Complexity:

   Best Case: O(1)
   Average Case: O(log n)
   Worst Case: O(log n)

Note: Binary Search requires a sorted array.


 Experimental Results

Test Setup:

Arrays of different sizes were used:

 Small (10 elements)
 Medium (100 elements)
 Large (1000 elements)

Each algorithm was tested on:

 Random arrays
 Sorted arrays

Observations:

1. Quick Sort performed significantly faster than Bubble Sort, especially on medium and large arrays.
   This is because Quick Sort has a much better time complexity (O(n log n)) compared to Bubble Sort (O(n²)).

2. As the array size increased, the performance gap became larger.
   Bubble Sort became very slow for large arrays, while Quick Sort remained efficient.

3. Sorted vs Random Data:

   Bubble Sort performed faster on sorted arrays due to early stopping (no swaps needed).
   Quick Sort performance was relatively stable, but can degrade in worst-case scenarios depending on pivot choice.

4. Binary Search was extremely fast compared to sorting algorithms, since it only requires O(log n) time.


Screenshots

<img width="628" height="689" alt="Снимок экрана 2026-04-28 в 22 19 23" src="https://github.com/user-attachments/assets/fe9cc4a8-a01d-45ba-928f-6032b5941726" />



Reflection

Through this assignment, I learned how different algorithms perform in practice and how important time complexity is when working with large datasets. Even though Bubble Sort is easy to understand, it becomes inefficient very quickly as input size grows. Quick Sort, on the other hand, is much more scalable and suitable for real-world applications.
I also observed that theoretical Big-O complexity generally matches practical performance, but actual execution time can still vary depending on input data (for example, sorted vs random arrays). One challenge I faced was understanding how to properly measure performance and ensure fair comparisons between algorithms.
Overall, this project helped me better understand algorithm efficiency and strengthened my Java programming and problem-solving skills.
