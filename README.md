Algorithms
==========
[![MIT](https://img.shields.io/dub/l/vibe-d.svg)](https://github.com/alexprut/Algorithms/blob/master/LICENSE)

Classic Algorithms and Data Structures implemented in C++

_Code written for practice. During my Master's degree in Computer Science at the University of Udine._

Algorithms Implemented
======================

|Algorithm|Average Cost|Worst-case Cost|
|---|---|---|
|[Insertion Sort](https://github.com/alexprut/Algorithms/blob/master/insertionSort.cpp)|O(n^2)|O(n^2)|
|[Merge Sort](https://github.com/alexprut/Algorithms/blob/master/mergeSort.cpp)|Θ(nlogn)|Θ(nlogn)|
|[QuickSort](https://github.com/alexprut/Algorithms/blob/master/quickSort.cpp)|O(nlogn)|O(n^2)|
|[Counting Sort](https://github.com/alexprut/Algorithms/blob/master/quickSort.cpp)|||
|[Binary Search](https://github.com/alexprut/Algorithms/blob/master/binarySearch.cpp)|O(logn)|O(logn)|
|[Bubble Sort](https://github.com/alexprut/Algorithms/blob/master/bubbleSort.cpp)|O(n^2)|O(n^2)|
|[Heapsort](https://github.com/alexprut/Algorithms/blob/master/binaryMaxHeap.cpp#L133)|O(nlogn)|O(nlogn)|

Data Structures Implemented
===========================
|Data Structure|Methods|
|--------------|-------|
|[Linked list](https://github.com/alexprut/Algorithms/blob/master/linkedList.cpp)|```insertFront(int value)``` - O(1), ```deleteFront()``` - O(1), ```isEmpty()``` - O(1)|
|[Double Linked list](https://github.com/alexprut/Algorithms/blob/master/doubleLinkedList.cpp)|```insertFront(int value)``` - O(1), ```deleteFront()``` - O(1)|
|[Queue](https://github.com/alexprut/Algorithms/blob/master/queue.cpp)|```enqueue(int value)``` - O(1), ```dequeue()``` - O(1), , ```isEmpty()``` - O(1)|
|[Stack](https://github.com/alexprut/Algorithms/blob/master/stack.cpp)|```pop()``` - O(1), ```push()``` - O(1), ```top()``` - O(1), ```isEmpty()``` - O(1)|
|[Binary Search Tree (BST)](https://github.com/alexprut/Algorithms/blob/master/binarySearchTree.cpp)|```insert(int value)```, ```search(int value)```, ```printInOrder()``` - Θ(n), ```printPreOrder()``` - Θ(n), ```printPostOrder()``` - Θ(n)|
|[Heap (binary max heap)](https://github.com/alexprut/Algorithms/blob/master/binaryMaxHeap.cpp)|```heapify(int index)``` - O(logn), ```insert(int value)``` - O(logn), ```deleteMax()``` - O(logn), ```buildHeap(vector<int> values)``` - O(n), ```heapSort()``` - O(nlogn)|

License
=======
Licensed under [MIT](https://github.com/alexprut/Algorithms/blob/master/LICENSE).
