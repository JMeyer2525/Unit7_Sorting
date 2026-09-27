# Unit 7 Discussion: Sorting Algorithms

## Overview

This assignment compares Bubble Sort and Merge Sort.

## Learning Objectives

- Implement Bubble Sort
- Implement Merge Sort
- Understand divide-and-conquer
- Compare algorithm efficiency

## Requirements

1. Test Bubble Sort and Merge Sort.
2. Use multiple datasets.
3. Demonstrate edge cases.
4. Analyze performance.
5. Create a real-world sorting example.

## Discussion Board Reflection

After completing the programming assignment, add this reflection to your initial discussion post in LEO.

Your reflection should be approximately 150–200 words and address the following questions:

1. What concepts or skills did you learn while completing this assignment?
This assignment has helped me understand sorting algorithms, recursion, and algorithm efficiency.
I learned that Bubble Sort working by repeatedly comparing adjacent values and swapping them when
they're in the wrong order. I also found out how Merge Sort uses a divide-and-conquer approach by 
splitting a list into smaller sections, sorting those sections, and then merging them back together.
2. What challenges did you encounter, and how did you overcome them?
A big challenge I encountered was understanding how the Merge Sort merge() function combined two
sorted lists. I overcame this by using separate indexes for each list and comparing the current values 
before adding them to the result. Testing empty lists, duplicate values, sorted lists, and reverse-sorted 
lists also helped me identify and handle different edge cases.
3. Compare and contrast each sorting algorithm based on efficiency differences, tradeoffs made, and when to each.
Bubble Sort was easier to implement and required less complex logic, but its O(n²) average and worst-case
performance made it inefficient for large datasets. Merge Sort required recursion and additional memory, but 
its O(n log n) performance made it much more efficient for larger datasets. I would use Bubble Sort for small 
datasets and Merge Sort when working with large amounts of data where performance and adaptability were more important.
