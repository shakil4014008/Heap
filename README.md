# Heap

Heapify Down Algorithm:

Start with the element that needs to be moved down. This element is usually the root element in a binary heap.
Compare the value of this element with its two children (if they exist) to find the largest (in case of a max heap) or the smallest (in case of a min heap) among them.
If the value of the current element is not the largest/smallest among the three (parent and two children), swap it with the largest/smallest child.
Move to the child with which you swapped the element and repeat steps 2 and 3 until the element reaches its correct position in the heap (i.e., it becomes greater than or equal to its children in a max heap, or less than or equal to its children in a min heap) or until it reaches a leaf node (a node with no children).
The goal of heapify down is to "bubble down" the element until it satisfies the heap property. This ensures that the largest element (in a max heap) or the smallest element (in a min heap) is at the root, making it efficient to access or remove the top element from the heap.

The complexity of heapify down is O(log n), where n is the number of elements in the heap, as it typically goes down through the height of the binary heap
