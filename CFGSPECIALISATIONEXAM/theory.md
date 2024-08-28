

1.1The deque module is part of collections library.

 1.2.Hierarchyical structure and connectivity. A tree has a hierarchyical 
structure where it has a root node and every other node has 
one parent, and there is a unique path between any two nodes. A graph
however has a genereal structure consistng of vertices connected 
by edges, they han have multiple paths between nodes, can contain
loops and do not necessarily have a hierarchical structure. The second
 difference is connectivity:A tree has all its nodes connected
and there is only one path between any two nodes whereas a graph
 can have  disconnected nodes and can contain cycles.


1.3.Definition of time complexity and space complexity:
Time complexity refers to the amount of time an algorithm takes to 
complete as a function of the input. It is typically expressed as Big O  
notation such as O(N), O(NlogN), O(N²). It helps determine how the execution of
time of an algorithm scales with the size of an input data.

Space complexity refers to the amount of memory space an algorithm requires to run
as a function of the input size.It also is expressed by the Big O notation. Space complexity
includes both the space needed for the input data and the additional space
required by the algorithm to perform computations.


1.4 Bubble sort algorithm nd its complexity: It is simplest sorting algorithm
that works repeatedly swapping the adjacent elements if they are in the wrong
order. This algorithm is not suitable for large data sets because its average
and worst-case time complexity is high (O(N²)). In Bubble sort algorithm, 
traverse from left and compare adjacent elements and the higher one is placed
at the right side, in this way the largest element is moved to the rightmost
end at first.This process is then continued to find the second largest and
place it and so on until the data is sorted (ref.Geeksforgeeks.org). In the best
case, the time complexity is O(N), the algorithm needs to make only one pass 
through the list with no swaps needed.In the worst case , the maximum number of 
passes is n-1 and each pass involves n-1 comparisons, resulting in O(N²) time 
complexity.

At the end of the first pass, the largest element is guaranteed to be in its correct
position at the end of the list. This is because, during the first pass, the algorithm
compares each adjacent pair and bubbles the largest element to the end of the list (ref.chatgpt)

1.5 LIFO: Last in First Out
FIFO: First in First Out

They are two fundamental principles that describe how data is managed 
in certain data structures.They determine the order in which elements 
are added and removed from a data structure.

LIFO: It means that last element that was added to the structure 
is the first one to be removes, an example could the stack of books, 
the last book that was added to the stack of books will be the first
to be put back in the book shelf.
Data structure: Stack: In a stack elements are added and removed 
from the same end, known as the top of the stack. The mos recent element
that was added, is removed the first. Stacks are used in scenarios like
undo mechanisms in text editors, where the last action performed
is the first to be removed.

FIFO:The first element added to the structure will be the first one to be removed.
An example could be a queue in a grocery store, where the first person 
in line is the first one to be served. In a Data Structure Queue , elements
are added at one end removed from the other end. The element that has 
been in the queue the longest is removed first.Practical operation examples
can be enqueue operation which is adding  an element to a queue, and 
retrieving one form a queue is called dequeue.(ref: realpython.com, chatgpt)

![screenshot.png](..%2F..%2FPictures%2Fscreenshot.png)