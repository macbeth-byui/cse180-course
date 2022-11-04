# CSE 180 Prepare 03 - Performance & Memory

When we look at an algorithm, we will always analyze the work that is performed.  We call this work a performance measure.  Performance can be represented either in steps (no units) or actual time (e.g. milliseconds).  We will organize the different types of performance using Big-O notation.

Algorithms frequently need to organize data into computer memory using data structures.  This week we will learn about the two fundamental data structures: array and linked list.  There are other data structures we will see this semester but they are all built on these two foundational structures.  The selection of data structures is important because it will affect the performance as well.  We will look at the Big-O notation for operations (e.g. searching, inserting, deleting) from arrays and linked lists.

## Reading

* Lesson 1 - Remainder of [Chapter 1: Introduction to Algorithms](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_007.html) - Big O Notation sub-sections inluding Exercises 1.3, 1.4, 1.5, and 1.6
* Lesson 2 - [Chapter 2: Selection Sort](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_008.html) - How Memory Works and Arrays and Linked Lists sub-sections including Exercises 2.1, 2.2, 2.3, 2.4, and 2.5.

Notes about reading:

* The tables comparing Arrays and Linked Lists in the reading are correct but incomplete.  There are scenarios where the performance is better or worse.  Here is a complete table which assumes that the linked list is a double linked list.  A doubly linked list means that we keep track of both the front and the end of the list and we can traverse in both directions.

|Operation|Arrays|Doubly Linked Lists|
|:-:|:-:|:-:|
|Reading by Index|$O(1)$|$O(n)$|
|Searching by Value|$O(n)$|$O(n)$|
|Inserting|$O(1)$ at the end; otherwise $O(n)$ due to right shift|$O(1)$ at the front or end; otherwise $O(n)$ to find location and $O(1)$ to insert.|
|Deleting|$O(1)$ at the end; otherwise $O(n)$ due to left shift|$O(1)$ at the front or end; otherwise $O(n)$ to find location and $O(1)$ to insert.

* For exercise 2.1, if we insert at the end, then it will be $O(1)$ for both Arrays and Doubly Linked Lists.  There is a cost if the array is full, but this doesn't affect the final performance over time.  We call this amortized time and you will learn more about that in CSE 381.  So, in the end, both data structures would work equally well.
* For exercise 2.5, you are comparing the new hybrid data structure with either a **sorted** array and a **sorted** doubly linked list (i.e. refer back to your analysis in the previous exercise for a sorted array).  Here is a modified solution based on our complete table above:

|Operation|Sorted Array|Doubly Linked List|Hybrid Data Structure|
|:-:|:-:|:-:|:-:|
|Search|$O(\log n)$ since we can use binary search|$O(n)$|$O(1)$ to lookup based on first the letter and $O(n)$ to search through the names (hopefully fewer, but still $O(n)$)|
|Insert|$O(n)$ since we have to search for the correct place to insert|$O(n)$ since we have to search for the correct place to insert|$O(1)$ to lookup based on the first letter and $O(1)$ to insert at the end of the doubly linked list.|

[![Creative Commons License - CC - BY](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
