# CSE 180 Prove 05

(c) BYU-Idaho - It is an honor code violation to post this
file completed or uncompleted in a public file sharing site.

**Instructions**: Answer each question using proper markdown notation as needed.  Use the preview view in Visual Studio Code (or other editor you may be using) to see the formatting, tables, and mathematical formula.  If you need to write code, first test in a separate file and then copy the code into this document using code fences.  Submit the markdown file (not a pdf) into I-Learn.


## Question 1

In your own words, describe the strategy of divide and conquer algorithms.

**Answer**:

## Question 2

Write the Algorithm Design Document (ADD) for QuickSort.  When writing your ADD, assume a randomly selected pivot as opposed to the selection of index 0 as the pivot (which was done in our example in class).

**Algorithm Name**:

QuickSort

**Abstract**:

(describe what problem this algorithm solves and the strategy)

**Inputs**:

(provide the list of inputs for the algorithm)

**Procedure**:

1. Describe step 1
2. Describe step 2
3. Describe step 3

(add more steps as needed)

**Outputs**:

(describe the expected output of the algorithm)

**Analysis**:

(describe the big-O notation in the average case)

## Question 3 (Worth 10% Bonus)

Implement in python the ADD you wrote for Quicksort using a randomly selected pivot using the starting code below:

```python
import random

# List Slicing:
#   data[a:b] - New list going from index a to b-1
#   data[:b] - New list going from index 0 to b-1
#   data[a:] - New list going from index a to the end
#   data[:] - Copy of the whole list
#   Note that if data is empty, then data[:0] or data[0:] result in []

# Random Numbers:
#    random.randint(a,b) - Select a random integer between a and b, inclusive.

def quicksort(l):
    # Put your code here
    pass

# Test Code
list1 = [3,1,5,2,6,8,3,4,6,2,1,6,3,2,6,4]
list2 = [random.randint(1,100) for _ in range(10000)]
list3 = [1]
list4 = []
print(quicksort(list1))
print(quicksort(list2))
print(quicksort(list3))
print(quicksort(list4))    
```
