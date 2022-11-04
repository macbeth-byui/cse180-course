# CSE 180 Prove 03

(c) BYU-Idaho - It is an honor code violation to post this
file completed or uncompleted in a public file sharing site.

**Instructions**: Answer each question using proper markdown notation as needed.  Use the preview view in Visual Studio Code (or other editor you may be using) to see the formatting, tables, and mathematical formula.  If you need to write code, first test in a separate file and then copy the code into this document using code fences.  Submit the markdown file (not a pdf) into I-Learn.


## Question 1

Put the following Big-O functions in order going from fastest to slowest.  You can use a graphing calculator like [Desmos](https://www.desmos.com/) to compare the different functions.  Included in the list is $O(n \log n)$.  This is different from $O(n)$ and $(\log n)$.  This performance occurs with sorting algorithms which we will see later in the semester.  Put a 1 for the fastest, 2 for the second fastest, and so on with 7 being the slowest for large values of $n$.

|Big-O Function|Performance Rank (1=fastest, 7=slowest)|
|:-:|:-:|
|$O(n^2)$||
|$O(n)$||
|$O(n \log n)$||
|$O(2^n)$||
|$O(1)$||
|$O(\log n)$||
|$O(n!)$||


## Question 2

If you counted the work in a algorithm to be $5n^3+2n^2+n+382$ where $n$ is the number of items in a list that the algorithm is using, what is the simplified Big-O notation for the algorithm?

**Answer**: 

## Question 3

Explain the strengths of an Array versus the strengths of a Doubly Linked List with respect to performance.

**Answer**: 

## Question 4

Explain why the performance of looking up a value by index in an Array is $O(1)$.

**Answer**:

## Question 5

What is the Big-O notation for each of the three functions in the following code:

```python
def do_something1(data):
    for x in data:
        for y in data:
            print(x,y,x*y)

def do_something2(data):
    first = 0
    last = len(data)-1
    while first < last:
        print("Finding the Middle Again")
        middle = (first + last) // 2
        last = middle - 1

def do_something3(data):
    for item in data:
        print(item)
```

**Answer**: 
* do_something1 :
* do_something2 :
* do_something3 :
