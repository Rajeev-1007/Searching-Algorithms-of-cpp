# Searching-Algorithms-of-cpp
# Name: Rajeev Ramesh Reddy E
# PRN: 24070123081

Aim:

To study, understand, and implement various searching algorithms in C++, analyze their working principles, compare their efficiency, and conclude the best suitable algorithm under different scenarios.

Software Used: Vs Code

Theory:

Searching algorithms in C++ are techniques used to locate specific elements within data structures like arrays, linked lists, or trees. Common types include linear search and binary search. Linear search scans each element sequentially, making it simple but inefficient for large datasets. Binary search, on the other hand, requires sorted data and divides the search space in half at each step, offering faster performance. These algorithms are foundational in computer science, helping optimize data retrieval and decision-making processes. Implementing them in C++ enhances understanding of control flow, iteration, recursion, and algorithmic efficiency in real-world applications.


Algorithms:

i) Algorithm: Binary Search in C++

 1. Initialize Search Bounds
- Set `low = 0` and `high = size - 1` to define the search range within the sorted array.

 2. Loop Until Bounds Meet
- Use a `while` loop that continues as long as `low <= high`.

 3. Calculate Midpoint
- Compute `mid = (low + high) / 2` to find the middle index of the current search range.

 4. Compare and Adjust
- If `arr[mid] == key`, return `mid` (key found).
- If `arr[mid] < key`, set `low = mid + 1` (search right half).
- If `arr[mid] > key`, set `high = mid - 1` (search left half).

 5. Return Result
- If the loop ends without finding the key, return -1 and display "Key not found."

ii) Algorithm: Linear Search in C++

 1. Define Search Function
- Create a function `linearSearch(int arr[], int size, int key)` to search for the target value.

 2. Traverse Array
- Use a `for` loop from index `0` to `size - 1` to check each element.

 3. Compare Each Element
- If `arr[i] == key`, return the index `i` (key found).

 4. Handle Not Found Case
- If the loop completes without a match, return `-1` (key not found).

 5. Display Result
- In `main()`, call the function and print whether the key was found or not using `cout`.

iii) Algorithm: Sequential Search in C++

 1. Define Search Function
- Create a function `sequentialSearch(int arr[], int size, int key)` to search for the target value.

 2. Initialize Index
- Start with index `i = 0` to begin scanning the array from the first element.

 3. Traverse and Compare
- Use a `while` loop to iterate through the array.
- If `arr[i] == key`, return index `i` (key found).

 4. Handle Not Found Case
- If the loop completes without a match, return `-1` to indicate the key was not found.

 5. Display Result
- In `main()`, call the function and print whether the key was found or not using `cout`.


Conclusion:

Searching algorithms in C++ are essential for locating data efficiently. Techniques like linear, sequential, and binary search help reinforce control flow, iteration, and decision-making. Understanding their logic and implementation builds a strong foundation for solving real-world problems and optimizing performance in larger, more complex data structures.
