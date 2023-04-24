# Selection-sort

Selection Sort is a simple sorting algorithm that sorts an array by repeatedly finding the minimum element from the unsorted part of the array and moving it to the beginning of the sorted part of the array. It does this by iterating over the unsorted portion of the array and selecting the smallest element in that portion. It then swaps the selected element with the first element of the unsorted portion, effectively adding it to the sorted portion of the array.

The algorithm works as follows:

Set the first element of the array as the minimum value.
Iterate over the unsorted portion of the array, starting from the second element, and compare each element with the current minimum value. If a smaller value is found, update the minimum value.
Once the end of the unsorted portion is reached, swap the minimum value with the first element of the unsorted portion, effectively adding it to the sorted portion of the array.
Repeat the above steps until the entire array is sorted.
Selection Sort has a time complexity of O(n^2), making it inefficient for large data sets. However, it has the advantage of requiring only a small amount of additional memory space, making it useful in situations where memory is a limiting factor.






