# Factorial



In mathematics, the factorial of a non-negative integer `n`, 
denoted by `n!`, is the product of all positive integers less 
than or equal to `n`. For example:

```
5! = 5 * 4 * 3 * 2 * 1 = 120
```

| n     | n!                          | 
| ----- | --------------------------: |
| 0     | 1                           |
| 1     | 1                           |
| 2     | 2                           |
| 3     | 6                           |
| 4     | 24                          |
| 5     | 120                         |
| 6     | 720                         |
| 7     | 5 040                       |
| 8     | 40 320                      |
| 9     | 362 880                     |
| 10    | 3 628 800                   |
| 11    | 39 916 800                  |
| 12    | 479 001 600                 |
| 13    | 6 227 020 800               |
| 14    | 87 178 291 200              |
| 15    | 1 307 674 368 000           |

# Fibbonaci

The fibonnaci sequence takes the sum of the two previous positive integers to generate the next one. It has two base cases: 0, and 1 (neither of which have 2 previous positive integers).
Every other integer has a fibbonaci value, as demonstrated in this table:  

| 0     | 0                           |
| 1     | 1                           |
| 2     | 1                           |
| 3     | 2                           |
| 4     | 3                           |
| 5     | 5                           |
| 6     | 8                           |
| 7     | 13                          |
| 8     | 21                          |
| 9     | 34                          |
| 10    | 55                          |
| 11    | 89                          |
| 12    | 144                         |
| 13    | 233                         |
| 14    | 377                         |
| 15    | 610                         |


## References

[Wikipedia Factorial](https://en.wikipedia.org/wiki/Factorial)
[Wikipedia Fibonnaci](https://en.wikipedia.org/wiki/Fibonacci_number)


# Selection Sort 

The selection sort algorithm sorts an array by repeatedly
finding the minimum element (considering ascending order) 
from unsorted part and putting it at the beginning

```
arr[] = 64 25 12 22 11

// Find the minimum element in arr[0...4]
// and place it at beginning
11 25 12 22 64

// Find the minimum element in arr[1...4]
// and place it at beginning of arr[1...4]
11 12 25 22 64

// Find the minimum element in arr[2...4]
// and place it at beginning of arr[2...4]
11 12 22 25 64

// Find the minimum element in arr[3...4]
// and place it at beginning of arr[3...4]
11 12 22 25 64 

```

## References

[geekforgeeks](https://www.geeksforgeeks.org/selection-sort/)

# Pascal's Triangle  

In mathematics, Pascal's triangle is a triangular array of the binomial coefficients. 
Each number is the numbers directly above it added together.

```
1
1 1
1 2 1
1 3 3 1
1 4 6 4 1
1 5 10 10 5 1
```

## References

[Pascal's Triangle](https://www.wikiwand.com/en/Pascal%27s_triangle)

# Bubble Sort

Bubble sort, sometimes referred to as sinking sort, is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted.

## References

[Bubble Sort](https://en.wikipedia.org/wiki/Bubble_sort)


# Inorder Traversal

Inorder Traversal is one of Depth First Search (DFS) methods used for Tree Traversals. Following is the implementation of Inorder Traversal of a Binary Tree using Iterative method.

```
   1
    \
     2
    /
   3

```
__Output:__ [1, 3, 2]

## References

[Tree Traversals](https://www.geeksforgeeks.org/tree-traversals-inorder-preorder-and-postorder/)