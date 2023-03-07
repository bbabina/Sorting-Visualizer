# Sorting-Visualizer
A pictorial representation demonstrating how Data Structures and Algorithms can be used to sort any data.



![Screenshot 2023-01-07 162427](https://user-images.githubusercontent.com/74191100/211145941-92a66622-9fcd-4c67-9255-aef4b82652c3.png)



# Visualization of the algorithms.
The visualizer basically plays with colors to better understand what is happening in the algorithm. The data here is the bars that are generated randomly with arbitrary heights. 

When the algorithm runs, these bars or segments change to three different colors – yellow, red, and green, each holding its own function.

The yellow segment represents that the algorithm is looking at that particular segment. If it is changing a certain segment it will mark it as red. If the final position of the segment is where it is now that is in a sorted position, it will mark it as green.

Once the algorithm is running, it disables all the buttons so that sorting can be performed uninterruptedly. Color and height are changed accordingly while the algorithm is working. 

## The algorithm used are: 

# Bubble Sort

Bubble Sort is an iterative sorting algorithm that imitates the movement of bubbles in sparkling water.
The bubbles represent the elements of the data structure.
In real practice, the bigger bubbles reach the top faster than smaller bubbles, and this algorithm works in the same way.
It iterates through the data structure and for each cycle compares the current element with the next one, and swaps them if they are in the wrong order.

The major drawback of this sorting technique is that it requires a lot of time because of its worst case as O(n2). So, it can be used for only a small set of data and only when we require a handful of swaps.

Bubble Sort is a simple algorithm to implement but not much effective in real-world scenarios.

# Insertion Sort

Insertion sort is a simple sorting algorithm that builds the final sorted array one item at a time. 

The algorithm divides the data structure into two sublists: a sorted one, and (n-1) set of elements still to sort. Initially, the sorted sublist is made up of just one element and it gets progressively filled. For every iteration, the algorithm picks an element on the unsorted sublist and inserts it at the right place in the sorted sublist. 

The average complexity being O(n2), the performance is directly proportional to the square of the input taken. In simple, the time taken for execution will take square times the input size.

It is really easy to implement and it’s efficient only on small data structures which are almost sorted. 

# Selection Sort

Selection Sort is an iterative and in-place sorting algorithm that divides the data structure into two sublists: the ordered one, and the unordered one.

The selection sort algorithm sorts an array by repeatedly finding the minimum element from the unordered part and putting it at the beginning. In every iteration of selection sort, the minimum element from the unordered subarray is picked and moved to the ordered sublist. 

The main advantage of the selection sort is that it performs well on a small list. Furthermore, no additional temporary storage is required beyond what is needed to hold the original list.

It retains the first k smallest element in its first k iterations.  So, you don’t need to sort all the data to obtain the first kth sorted data.


# Merge Sort

Merge Sort is a sorting algorithm based on the Divide and Conquer technique. Basically, it divided the data into different groups, sorts data into groups, and merges them to get complete sorted data. 

The first stage is where the list is split until it forms individual elements called sub-lists. After this, the ‘merge’ stage begins. Here the sub-lists are paired up and are arranged according to the order stated. These paired lists are paired again to form groups and are again arranged according to the intended order. This process happens until the sub-lists form one list. 

The complexity O(nxlogn) denotes the logarithmic time which makes this sorting technique faster than the other. But, because of space complexity of O(n), it requires more space.

It works perfectly well for a large set of data because of its low time complexity. But, it requires at least twice the memory than other sorts. 


# Heap Sort 

Heap Sort is an in-place iterative sorting algorithm based on auxiliary data structures called heap.

Heap sort can be thought of as an improved selection sort. Alike selection sort, heapsort divides its input into a sorted and an unsorted region, and it iteratively shrinks the unsorted region by extracting the largest element from it and inserting it into the sorted region.

Heap sort works by transforming the list of items to be sorted into a heap data structure that is – a binary tree with heap properties. In a binary tree, every node has at most, two descendants. A node possesses the heap property when none of its descendants have greater values than itself. The largest element of the heap is removed and inserted into the sorted list. The remaining sub-tree is transformed into a heap again. This process is repeated until no elements remain. 

While other sorting algorithms may grow exponentially slower as the number of items to sort increases, the time required to perform Heap sort increases logarithmically. This suggests that Heap sort is particularly suitable for sorting a huge set of data.

The Heap sort algorithm is widely used because of its efficiency. 


# Quick Sort

Quick Sort is a sorting algorithm based on splitting the data structure into smaller partitions and sorting them recursively until the data structure is sorted.

This division in partitions is done based on one element, called a pivot. All the elements bigger than the pivot get placed on the right side of the structure, and the smaller ones to the left.  This occurs recursively to the two partitions and so on.

This partition technique based on the pivot is called Divide and Conquer.

It has an efficient average case compared to any other sort algorithm. But, it is not a stable sort. That means the order of equal elements may not be preserved.
Quicksort is one of the most efficient sorting algorithms, and this makes it one of the most used as well. 




