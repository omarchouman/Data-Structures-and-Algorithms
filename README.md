# Data Structures & Algorithms

This Repository is made for anyone who wants to learn about Big-O Notation, Data Structures, and Algorithms.

#### We Will Be Discussing Big-O Notation
---
- [What is Big-O?](#what-is-big-o)
- [Big-O Cases From Best To Worst](#big-o-cases)
- [Big-O Basic Rules](#big-o-rules)

#### We Will Be Covering The Well-Known Data Structures
---
- [Array Data Structure: (Fixed Size)](#array-structure)
- [Dynamic Array Data Structure: (Double Size)](#dynamic-array-structure)
- [Linked List Data Structure](#linked-list)
- [Stack Data Structure](#stack)
- [Queue Data Structure](#queue)
- [Hash Table Data Structure](#hash-table)
- [Tree Data Structure](#tree)
- [Graph Data Structure](#graph)
- [Heap Data Structure](#heap)
- [Trie Data Structure](#trie)

#### We Will Be Discussing Some Of The Famous Algorithms Like
---
- **Sorting Algorithms:**
  - [QuickSort](#quicksort)
  - [BubbleSort](#bubblesort)
  - [MergeSort](#mergesort)
- **Searching Algorithms:**
  - [Linear Search](#linear-search)
  - [Binary Search](#binary-search)
- [Breadth First Search (BFS) (coming soon)](#bfs-coming-soon)
- [Depth First Search (DFS) (coming soon)](#dfs-coming-soon)

## What is Big-O?
---
Big-O is the worst-case scenario of the code, which means the high time complexity the code gets executed in.

### Big-O Cases From Best To Worst
- O(logn) (Logarithmic)
- O(1)
- O(n) (Linear)
- O(n^2) (Quadratic)
- O(2^n) (Exponential)
- O(n!) (Worst Case)

![Big-O Image](images/Big-O.jpeg)

### Big-O Rules
- +, -, /, x, if (1 Step) (Constant)
- Loop, SubRoutine, Function (n Steps)
- To Access Memory (2 Steps)

## Array Structure (Fixed Size)
---
An array is a collection of elements identified by their index.

### Time Complexity of An Array:
- Access = O(1)
- Search, Insert, and Delete = O(n)

![Array Image](images/Array.png)

## Dynamic Array Structure (Double Size)
---
A dynamic array doubles the size of your normal array to allow you to add new items to it.

## Linked List Data Structure
---
Linked List is basically when you have a bunch of connected nodes where each node takes a value and then takes the address of the next node.

#### Double Linked List:
- Previous Address
- Value
- Next Address

![Single Linked List Image](images/Single%20Linked%20List.png)

![Double Linked List Image](images/Double%20Linked%20List.png)

## Stack Data Structure
---
Stack is a linear data structure that follows FILO (First In Last Out) mechanism.

3 basic operations are performed in a stack:
- Push: Adds an item to the stack (top + 1)
- Pop: Removes an item from the stack (top – 1)
- Peek or Top: Returns top element stack

![Stack Image](images/Stack.png)

## Queue Data Structure
---
Queue is a listing data structure that follows FIFO (First In First Out).

2 basic operations are performed in the queue:
- Rear: First Element in a Queue
- Front: Next or Last Element in a Queue

Queue starts from Rear and ends at Front

![Queue Image](images/Queue.png)

## Hash Table Data Structure
---
In a hash table, data is stored in an array format, where each data value has its own unique index value.

#### Key Value Pairs
##### Hash Table Easiest Algorithm:  item % size

![Hash Table Image](images/Hash%20Table.png)

## Algorithms
---
### QuickSort
---
Quicksort is a divide and conquer algorithm; it follows the partitioning procedure. Imagine some students standing in a line, these students should be arranged (Sorted) by their height. So what options do we have here?

![Students in Line Image](images/students-in-line.jpg)

We Got 2 Options:

1. Teacher can go and find each student's place 1 by 1.
2. Students can arrange themselves.

Now, which option is better?

Clearly, it's option 2 right? Why?

Students arranging themselves would take less time than the teacher going for their
