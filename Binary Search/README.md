## Problem

In computer science, binary search, also known as half-interval search, logarithmic search, or binary chop, is a search algorithm that finds the position of a target value within a sorted array. Binary search compares the target value to the middle element of the array. If they are not equal, the half in which the target cannot lie is eliminated and the search continues on the remaining half, again taking the middle element to compare to the target value, and repeating this until the target value is found. If the search ends with the remaining half being empty, the target is not in the array.


## Complexity Analysis
#### Space Complexity: O(n).
- Binary search requires three pointers to elements, which may be array indices or pointers to memory locations, regardless of the size of the array. Therefore, the space complexity of binary search is O(n) in the word RAM model of computation.

## Example
![Binary Search](https://i.pinimg.com/originals/e2/9a/31/e29a31c78bcc0d07c612adc77acc09a0.gif)

