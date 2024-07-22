# mergeSort
 Merge Sort is a classic divide-and-conquer algorithm used for sorting arrays. It's known for its stable O(n log n) time complexity and is often preferred for its predictable performance across various input scenarios. Here’s an overview of how Merge Sort works in Java, focusing particularly on the recursion involved:


Merge Sort Algorithm Overview:
Divide: The array is recursively divided into halves until each subarray contains a single element.

Conquer: After division, the subarrays are merged back together in sorted order.

Merge Operation: During the merge step, two sorted halves are combined to produce a single sorted array.

Recursive Approach in Java:
In Java, Merge Sort is commonly implemented using a recursive approach. Here’s a step-by-step breakdown of how recursion is utilized in Merge Sort:


Explanation:
merge method takes the original array arr, and indices low, mid, and high.
It creates a temporary array temp to hold the merged result.
Using pointers (left for the left subarray and right for the right subarray), it compares elements and fills temp in sorted order.
After merging, it copies the elements from temp back into the original array arr.
Key Points:
Base Case: Merge Sort stops dividing when the segment size is 1 (low >= high), ensuring it sorts efficiently even for small arrays.
Recursive Calls: Each recursive call divides the problem into smaller subproblems until reaching the base case.
Merge Operation: Combines sorted halves to produce a fully sorted array, utilizing temporary space efficiently.
Conclusion:
Merge Sort's recursive nature allows it to efficiently sort arrays by dividing the problem into manageable subproblems and then combining the solutions. In Java, careful handling of indices and temporary storage ensures that the recursion opera
