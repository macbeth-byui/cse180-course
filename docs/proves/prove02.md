# CSE 180 Prove 02

(c) BYU-Idaho - It is an honor code violation to post this
file completed or uncompleted in a public file sharing site.

**Instructions**: Answer each question using proper markdown notation as needed.  Use the preview view in Visual Studio Code (or other editor you may be using) to see the formatting, tables, and mathematical formula.  If you need to write code, first test in a separate file and then copy the code into this document using code fences.  Submit the markdown file (not a pdf) into I-Learn.


## Question 1

What is the maximum number of steps (worst case) to find something in a sorted list of 1 million items using linear search?

**Answer**: 

## Question 2

What is the maximum number of steps (worst case) to find something in a sorted list of 1 million items using binary search?

**Answer**: 

## Question 3

What is the maximum number of steps (worst case) find something in a sorted list of 1 trillion items using binary search?

**Answer**: 

## Question 4

During class we created the Algorithm Description Document (ADD) for binary search.  Lets modify the problem so that we assume that the list is sorted in descending order (larger values are first).  The name of this modified algorithm, the inputs, and the outputs are already given for you below.  Note that instead of displaying a message that we found the item (like we did in class), we are returning a True or a False. You need to provide the Abstract, Procedure, and Analysis.

**Algorithm Name**:

Descending Binary Search

**Abstract**:

(describe what problem this algorithm solves and the strategy)

**Inputs**:

* data - list of values sorted in descending order
* target - what we are looking for in the data

**Procedure**:

1. Describe step 1
2. Describe step 2
3. Describe step 3

(add more steps as needed)

**Outputs**:

* True if the target was found.
* False if the target was not found.

**Analysis**:

(describe the maximum number of steps in the worst case)

## Question 5 (10% Bonus Points)

Implement in python the ADD you wrote for the Descending Binary Search using the start code below:

```python
def descending_binary_search(data, target):
    # Add Code Here
    pass

# Test Code
data = [88, 72, 61, 59, 44, 36, 29, 18]  # Start with a sorted list in descending order
print(descending_binary_search(data, 10)) # False
print(descending_binary_search(data, 18)) # True
print(descending_binary_search(data, 29)) # True
print(descending_binary_search(data, 36)) # True
print(descending_binary_search(data, 44)) # True
print(descending_binary_search(data, 50)) # False
print(descending_binary_search(data, 59)) # True
print(descending_binary_search(data, 61)) # True
print(descending_binary_search(data, 72)) # True
print(descending_binary_search(data, 88)) # True
print(descending_binary_search(data, 99)) # False


