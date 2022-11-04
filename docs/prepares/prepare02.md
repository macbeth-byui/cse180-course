# CSE 180 Prepare 02 - Searching & Documenting

The first software algorithm that we will look at this semester is a searching algorithm.  Actually, the searching algorithms are not exclusive to just software.  You have probably performed this algorithms countless times manually without a computer.  We will compare two algorithms:

* Linear Search
* Binary Search

We will also explore how to document an algorithm.  Your reading will include a document created by the United States Department of Defense which defines how a software developer contracting with the United States government should document all algorithms.  The government calls the document an Algorithm Description Document (ADD).  This semester, we will describe our algorithms a little bit less rigoursly.  However, we will identify the following for many of our algorithms (including binary search this week):

* Algorithm Name
* Abstract - What does the algorithm do?
* Inputs - What do we require to start with before running the algorithm (the ADD document describes this as the Data Dictionary Variables)
* Procedure - List the discrete steps written out in english.
* Outputs - What do we expect after running the algorithm?
* Analysis - What was the timing performance of the alogirthm?

## Reading

* Lesson 1 (First class of the week) - [Chapter 1: Introduction to Algorithms](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_007.html) - Binary Search sub-sections including Exercises 1.1 and 1.2
* Lesson 2 (Second class of the week) - [Algorithm Description Document](DI-EDRS-82219.pdf)

Notes about reading:

* The code examples in the book use Python 2.  All the examples in class will use Python 3.  The biggest difference is in Python 2 we can print to the screen: `print "hello"` whereas in Python 3 we use parentheses: `print("hello")`.
* You should complete the exercises in the book as part of your reading and studying time.  The answers are in the back of the book.  You will not submit the work you do on these exercises.
* The solution to exercises 1.1 and 1.2 are wrong and should be 1 more than the value shown in the book.  We will demonstrate this in class.
* If you want to see a very big example of an ADD, take a look at the ADD for the [Landsat Calibration Validation](https://www.usgs.gov/media/files/landsat-8-9-calibration-validation-algorithm-description-document) algorithms from the United States Geological Service (USGS).  Obviously you don't have time to read even 1% of this document, but it may be useful to scan through it and look for both discrete algorithm steps and the level of detail presented.

[![Creative Commons License - CC - BY](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
