# Data Structure
**Way of organizing or storing data as per your scenarios and needs so that it can be access or modify in efficient way.**

- # 500-600 Knowing data structures Types
- Array
- Bit Array
- Bit Field
- Bitboard
- Bitmap
- Circular buffer
- Control Table
- Image
- Dope vector
- Dynamic Array
- Gap buffer
- Hashed Array Tree
- Hightmap
- Lookup Table
- Matrix
- Parallel Array
- Sorted Array
- Spare Matrix
- iliffe vector
- Variable-length Array
- Lists
- Doubly Linked List
- Array List
- Linked List
- Self-Organizing List
- Skip List
- Unrolled Linked list
- VList
- Conc-Tree List
- Xor Linked list
- Zipper
- Different List
- Free List
- Trees
- Binary Trees
- AA Tree
- AVL Tree
- Binary Search Tree
- Binary Tree
- Cartesian Tree
- Left-Child right-sibling binary tree
- Order statistic tree
- Pagoda
- Randomized binary Search tree
- Red-Black tree
- Rope
- Scapegoat Tree
- Self-Balancing Binary Search Tree
- Splay Tree
- T-Tree
- Tango Tree
- Threaded Binary Tree
- Top Tree
- Treap
- WAVL tree
- Weight-balanced tree
- B- trees
- B- tree
- B+ tree
- B*- Tree 
- B Sharp tree
- Dancing Tree
- 2-3 Tree
- 2-3-4 Tree
- Queap
- Fusion Tree
- Bx-Tree
- AList
- Heaps
- Heap
- Binary Heap
- B-Heap
- Weak Heap
- Binomial Heap
- Fibonacci Heap
- AF-Heap
- Leonardo Heap


## ADT - Abstract Data Type 
__way to catagories Data Structure Type__

## Algorithm (All Go in a Rythm)
__Step by step procedure/Formula to solve the problem. Time tested algorithms are there to solve the problems__

To classify as an algorithm, it should satisfy 5 important characteristics
1. Input - Well define input
2. Output - well define outputs
3. Precise Steps - Steps of an algorithm should be clear 
4. Finite - Start and End should be there. Not in infinite loop
5. Uniqueness - Every steps of an algorithm output of the step give input for next step or used by any below step


## Big O Notation
__How your algorithm will perform when input data increase__

__O(1) - Performance will remain constant when input data increases__
```csharp
//O(1) - Constant
void function1(List<string> data) {
    string ste = data[0];
    //logic
}
```

### n - Record
### O - Performance ratio 

__O(n) - As a number of record increases, time will also increase - Linear way__
```csharp
//O(n) - Linear
void function2(List<string> data)
{
    foreach(var stre in data)
    {
        //Some logic
        if(str == "test")
        {
            return;
        }
    }
}
```

__O(n^2) or O(2n) - Time is twice of the record__
```csharp
//O(2n) or O(n^2) - Quadratic
void function3(List<string> data)
{
    foreach(var str in data)
    {
        foreach(string str1 in data)
        {
            //Logic
        }
    }
}
```

__Algorithm will work in performance point view - Time vs Number of Records__

> 1. O(1)
> 2. O(logn)
> 3. O(n)
> 4. O(nlogn)
> 5. O(2n)
> 6. O(n^2)

> _log n - it will initially performance decrease, but later on is the same or very minimal_

> _1 and 2 good, remains bad zone_

> _Bit O helps to identify algorithm good or bad on performance perspective_

> _DS and Algorithms should be balance_
