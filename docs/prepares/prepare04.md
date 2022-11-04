# CSE 180 Prepare 04 - Sorting & Recursion

If the Binary Search algorithm requires data to be sorted, it is probably a good idea that we find an algorithm to sort data.  

This week we will identify an alogrithm which is not the best performing.  To achieve a better algorithm we will need to learn a technique called Recursion.  This will allow us next week to explore a better sorting algorithm and begin to discover different classifications of algorithms.

## Reading

* Lesson 1 - Remainder of [Chapter 2: Selection Sort](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_008.html) - Selection Sort sub-section.

* Lesson 2 - All of [Chapter 3: Recursion](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_009.html) - Including exercises 3.1 and 3.2.

Notes about reading:

* The code presented for the Selection Sort algorithm in the book is correct and has $O(n^2)$ performance.  However, it requires the creation of a brand new list.  We say that this has a memory requirement of $O(n)$.  If we find an algorithm that sorts the list in-place (i.e., does not require a new list), then we have a better memory requirement of $O(1)$.  We will look at both algorithms during class.  To achieve an in-place selection sort, we will find the smallest value and swap it with the first element of the list.  In effect, we are moving the smaller items to the left.  In Python, if we want to swap two variables, we can use the code `x, y = y, x`
* In class we will look at the factorial problem as an example of simple recursion.  To see the call stack for this problem, take a look at this website:  [Recursive Factorial](https://www.cs.usfca.edu/~galles/visualization/RecFact.html)

[![Creative Commons License - CC - BY](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
