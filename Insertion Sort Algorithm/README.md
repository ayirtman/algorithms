## Problem

Insertion sort iterates, consuming one input element each repetition, and grows a sorted output list. At each iteration, insertion sort removes one element from the input data, finds the location it belongs within the sorted list, and inserts it there. It repeats until no input elements remain.

Sorting is typically done in-place, by iterating up the array, growing the sorted list behind it. At each array-position, it checks the value there against the largest value in the sorted list (which happens to be next to it, in the previous array-position checked). If larger, it leaves the element in place and moves to the next. If smaller, it finds the correct position within the sorted list, shifts all the larger values up to make a space, and inserts into that correct position.

The resulting array after k iterations has the property where the first k + 1 entries are sorted ("+1" because the first entry is skipped). In each iteration the first remaining entry of the input is removed, and inserted into the result at the correct position, thus extending the result:


## Complexity Analysis
#### Best: 
- O(n) time | O(1) space - where n is the length of the input array
#### Average: 
- O(n^2) time | O(1) space - where n is the length of the input array
#### Worst: 
- O(n^2) time | O(1) space - where n is the length of the input array

## Example
![Insertion Algorithn](https://upload.wikimedia.org/wikipedia/commons/4/42/Insertion_sort.gif)

## References
- [Wikipedia](https://en.wikipedia.org/wiki/Insertion_sort)

