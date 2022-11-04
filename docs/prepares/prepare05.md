# CSE 180 Prepare 05 - Divide & Conquer

Now that we have learned the basics of recursion, we can explore our first category of algorithms called Divide and Conquer.  Instead of trying to solve the whole problem, we will divide the problem and recursively solve it until we get to a base case.  You have already used this when we looked at the recursive solution to the binary search problem last week.  In addition to some list processing problems, we will also look at two improved sorting algorithms that use divide and conquer.

## Reading

* Lesson 1 - First half of [Chapter 4: Quicksort](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_010.html) - Including exercises 4.1, 4.2, 4.3, and 4.4.

* Lesson 2 - Remainder of [Chapter 4: Quicksort](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_010.html) - Including exercises 4.5, 4.6, 4.7, and 4.8

Notes about reading:

* We will present a different solution in class to the list max problem 4.4. 
* Take note of the short section in the reading called "sneak peak at functional programming".  Duirng class we will compare Python solutions with Erlang solutions (just for fun) for divide and conquer algorithms.
* The book mentions mergesort is an $O(n \log n)$ algorithm but it doesn't desribe how it works.  We will discuss this in class.  You can see a visualization of the mergesort algorithm here: https://visualgo.net/en/sorting  (click on "MER" for MergeSort
* The QuickSort algorithm in the book and the one we will see in class does not sort in place.  An in-place sort does not require any additional memory to perform the sort.  To see a visualization of an in-plae QuickSort, use the same link above but click on "QUI" for QuickSort.

[![Creative Commons License - CC - BY](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
