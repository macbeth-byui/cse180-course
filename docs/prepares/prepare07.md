# CSE 180 Prepare 07 - Dijkstra's Algorithm

The Breadth-First Algorithm allowed us to find the shortest path of an unweighted graph.  The graph was unweighted which meant we counting how many "hops" between nodes were required to get from one node to another.  However, if you think of a physical road map, the roads (edges) between intersections (nodes) do have mileage (weight) between them.  To find the shortest path between two nodes in a weighted graph, we will use the Dijkstra Algorithm.  

## Reading

* Lesson 1 - First half of [Chapter 7: Djikstra's Algorithm](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_013.html) - all subsections before the Implementation section.

* Lesson 2 - Remainder of [Chapter 7: Djikstra's Algorithm](https://learning.oreilly.com/library/view/grokking-algorithms/9781617292231/OEBPS/Text/kindle_split_013.html) - The remainder of the chapter including exercise 7.1

Notes about reading:

* The reading demonstrates the algorithm with directed weighted graphs only. The reading implies that you cannot use Dijkstra on an undirected graph which is misleading.  In class, we will use the algorithm with both directed and undireted graphs.

[![Creative Commons License - CC - BY](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
