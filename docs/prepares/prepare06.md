# CSE 180 Prepare 06 - Graphs & Breadth-First Search

After learning about Divide and Conqueuer with recursion, our second strategy for algorithm design is to consider graphs.  Over the next two weeks we will explore the graph and two algorithms to navigate those graphs.  During this first week, we will look at the Breadth-First Search.  Breadth-First will allow us to determine if there is a path between two nodes of a graph and also find the shortest path in terms of connections (e.g. edges).

## Reading

* Lesson 1 - First half of [Chapter 6: Breadth-first search](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_012.html) - up until exercises 6.1 and 6.2.

* Lesson 2 - Remainder of [Chapter 6: Breadth-first search](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_012.html) - Including exercises 6.3, 6.4, and 6.5.

Notes about reading:

* In Week 3 we learned about the dynamic array and the doubly linked list.  In Python, if you want a dynamic array, then you can use the list (`myList = [1,2,3]`).  If you want a doubly linked list, you can use a `deque`.  A doubly linked list is commonly used to implement a queue.  The phrase `deque` refers to "double ended queue" which is implemented with a doubly linked list.  Use the function `append` to add (or enqueue) and the function `popleft` to remove (or dequeue) from the `deque`.
* The reading assumes you know what a dictionary is.  If you need a refresher, take a look at change 5 in the book.  Graphs are frequently implemented using a hashtable which provides a quick lookup table.  We will also demonstrate how to use dictionaries in class.
* In class we will present a slightly modified version of the Breadth-First Algorithm that will use a `set` (like a dictionary but just the keys) to hold the nodes we have already visisted.  We will also modify the algorithm to keep track of the path length and path.

[![Creative Commons License - CC - BY](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
