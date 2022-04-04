# Insertion-Sort
## Kodluyoruz Data Structures Project1

### Array: [22,27,16,2,18,6]
- 1. step: [22,27,16,2,18,6]
- 2. step: [16,22,27,2,18,6]
- 3. step: [2,16,22,27,18,6]
- 4. step: [2,16,18,22,27,6]
- 5. step: [2,6,16,18,22,27] **the result.**

n + (n-1) + (n-2) ... +1) as it progresses , Big-O Notation: O(n^2)

-Best Case: The number is 2 , Big-O Notation: O(n)

-Average Case: The number is 16, Big-O Notation: O(n^2)

-Worst Case: The number is 27, Big-O Notation: O(n^2)

- 18 is average case. Because it's in the middle of the array.


### Array: [7,3,5,8,2,9,4,15,6]

- 1. step: [3,7|5,8,2,9,4,15,6]
- 2. step: [3,5,7,8|2,9,4,15,6]
- 3. step: [2,3,5,7,8,9|4,15,6]
- 4. step: [2,3,4,5,7,8,9|15,6]
- 5. step: [2,3,4,5,6,7,8,9,15]
