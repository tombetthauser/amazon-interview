![](https://i2.wp.com/webadictos.com/media/2018/11/amazon-buen-fin-2018.gif?resize=640%2C350&ssl=1)


# The Amazon Interview

### A Starter List of Questions for General Practice

You don't have to be preparing for a FAANG interview to benefit from studying data structures and algorithms as if you were. Because of their size and popularity FAANG interview questions are extremely well documented and in many cases are intended to be publicly transparent. Because of this many other companies model their interview questions on those used by FAANG companies. And as is the case with most companies, the technical questions used by FAANG companies can be found for the most part on sites like Leetcode. 

The following is a starter list for applicants preparing for Amazon interviews and can act as a good starter list for general technical interview preparation. Listed beneath the prompt descriptions are hints / reminders for optimal solutions that are in many cases difficult or nearly impossible to discover within a reasonable time limit, and beneath these are links to the problems on leetcode and external links to walkthroughs in Python.

Remember, in the world of Leetcode, sometimes "Easy" isn't easy and "Hard" isn't hard and if there isn't a hint listed for a problem yet check the Leetcode discussion section and / or youtube until you can make sense of it and find your own path!

---

<!--
Table of Contents:

Arrays and Strings (21 / 21)
* first unique character in string
-->

### First Unique Character in String
```Topic: Arrays | Leetcode: Easy 💚```

Find the first non-repeating letter in a string and return its index number.

[leetcode](https://leetcode.com/problems/first-unique-character-in-a-string/) | [youtube](https://www.youtube.com/watch?v=wlRezT0b5MI)

```
Hint: Use a hash map and multiple iterations.
```
<!-- 
Iterate over the input string once and create a counts hash table.
Iterate over the string a second time.
Check the hash table to see if there is exactly one 
-->

---



<!--
* integer to english words
    * two sum
    * string to integer (atoi)
    * integer to roman
    * 3sum
    * implement strStr()
    * group anagrams
    * compare version numbers
    * missing number
    * most common word
    * trapping rain water
    * longest substring without repeat
    * container with most water
    * roman to integer
    * 3sum Closest
    * rotate image
    * minimum window substring
    * product of array except self
    * valid parentheses
    * reorder log files

Linked Lists (3 / 6)
    * add two numbers
    * reverse nodes in k-group
    * reverse linked list
    * merge two sorted lists
    * copy list with random pointer
    * merge k sorted lists

Tree and Graphs (1 / 13)
* Number of Islands
  * Validate BST
  * Binary Tree Level Order Traversal
  * Binary Tree Maximum Path Sum
  * Word Ladder
  * Course Schedule
  * Diameter of Binary Tree
  * Flood Fill
  * Symmetric Tree
  * Binary Tree Zigzag Level Order Traversal
  * Word Ladder II
  * Lowest Common Ancestor of a B...
  * Cut Off Trees of Gold Event

Recursion (0 / 4)
    * Letter Combinations of a Phone...
  * Word Search
    * Generate Parentheses
  * Word Search II

Sorting & Searching (0 / 8)
      * Merge Sort
      * Quick Sort
      * Insertion Sort
* Kth Largest Element in an array ☎️
      * Algo Expert Heaps
      * Algo Expert Quick Sort
  * Median of Two Sorted Arrays
  * Merge Intervals
  * Top K Frequent Elements
  * Search in Rotated Sorted Array
  * Two Sum II (input sorted)
  * Meeting Rooms II
  * K Closest Points to Origin

Dynamic Programming (0 / 5)
    * Longest Palindromic substring
  * Best Time to Buy and Sell Stock
  * Coin Change
  * Maximum Subarray
  * Word Break

Design (0 / 7)
* LRU Cache
        - [x] Implement Linked List
  * Find Median from Data Stream
  * Design Tic-Tac-Toe
  * Maximum Frequency Stack
  * Min Stack
  * Serialize and Deserialize Binary Tree
  * Design Search Autocomplete System

Others (0 / 4)
* Prison Cells After N Days
  * Reverse integer
  * Partition Labels
  * Second Highest Salary
—————————————————————————

From Random Persons List

Double Down on These:
* Two Sum
* Longest Palindromic Substring
* Merge Two Sorted Lists
* Generate Parentheses
* Merge Intervals
* Copy List with Random Pointer
* Top K Frequent Elements
* Partition Labels
* Most Common Word
* K Closest Points to Origin

Not on Leetcode List:
* Spiral Matrix II
* Unique Paths II 
* Minimum Path Sum
* Unique Binary Search Trees
* Two Sum II - Input array is sorted
* Search a 2D Matrix II
* Linked List Random Node
* 01 Matrix
* Subtree of Another Tree
* Top K Frequent Words 
* Reorganize String
* Reorder Data in Log Files 
* Prison Cells After N Days
* Subarrays with K Different Integers
* Rotting Oranges
* Distant Barcodes
* Number of Dice Rolls With Target Sum
* Critical Connections in a Network
* Search Suggestions System

-->


### Two Sum 
```Topic: Arrays | Leetcode: Easy 💚```

Given an array of integers and a value, determine if there are any two integers in the array whose sum is equal to the given value.

[leetcode](https://leetcode.com/problems/two-sum/) | [youtube](https://www.youtube.com/watch?v=KLlXCFG5TnA)

```
Hint: Use a hashmap to log the complements of each number.
```
<!-- Use a hashmap to log the complements of each number.
Complements represent the other number you're looking for that to make target sum.
When you find one your looking for you're done! -->

---

### Move Zeros to the Left

```Topic: Arrays | Leetcode: Easy 💚```

Move all zeros to the left of an array while maintaining its order.

```
Hint: Use a pointer / pointers. Watch out for order.
```
<!-- Depends on zeros to end or begining. Either way use pointers. 
If zeros to end, use a left pointer and iterate the right normally. 
If zeros to beginning make left and right pointers meet in the middle. -->

[leetcode](https://leetcode.com/problems/move-zeroes/) | [youtube](https://www.youtube.com/watch?v=aayNRwUN3Do)

---

### Delete Node with Given Key

```Topic: Linked Lists | Leetcode: Easy 💚```

You are given the head of a linked list and a key. You have to delete the node that contains this given key.
Harder version, you aren't given the head but just the node. Sit on that one.

[leetcode](https://leetcode.com/problems/delete-node-in-a-linked-list/) | [youtube (related not exact problem)](https://www.youtube.com/watch?v=XVuQxVej6y8)

```
Hint: Dont create a new node.
```
<!-- No trick if you're given the head and a target val.
If you're just given the node you basically turn the node into it's neighbor.
Also disconnect it's neighbor from the linked list just in case. -->

---

### Copy Linked List with Random Pointers 

```Topic: Linked Lists | Leetcode: Medium 🧡```

You are given a linked list where the node has two pointers. The first is the regular ‘next’ pointer. The second pointer is called ‘arbitrary_pointer’ and it can point to any node in the linked list.
 
Your job is to write code to make a deep copy of the given linked list. Here, deep copy means that any operations on the original list (inserting, modifying and removing) should not affect the copied list.

[leetcode](https://leetcode.com/problems/copy-list-with-random-pointer/) | [youtube](https://www.youtube.com/watch?v=5Y2EiZST97Y)

```
Hint: Make a hashmap where the keys and values are node instances.
```
<!-- Make a crazy hashmap where the keys are the original nodes and the values are new copied versions of the nodes.
Then iterate back through and assign all pointers of node duplicates to their respective duplicates.
Dont forget to cover keying errors if pointers point to None.
Also don't forget input edge case of the head being None. -->

---

### Mirror Binary Trees

```Topic: Binary Trees | Leetcode: Easy 💚```

Given the root node of a binary tree, swap the 'left' and 'right' children for each node. 

[leetcode](https://leetcode.com/problems/invert-binary-tree/) | [youtube](https://www.youtube.com/watch?v=OnSn2XEQ4MY)

```
Hint: Recursion
```

---

### Check if Two Binary Trees are Identical

```Topic: Binary Trees | Leetcode: Easy 💚```

Given the roots of two binary trees, determine if these trees are identical or not.


```
Hint: Make sure to keep track of your p's and q's. Recursion. And don't forget the elvis operator that isn't actually an elvis operator. Spicy!
```

[leetcode](https://leetcode.com/problems/same-tree/) | [youtube](https://www.youtube.com/watch?v=vRbbcKXCxOw)

---

### String Segmentation

```Topic: Strings | Leetcode: Medium 🧡```

[leetcode](https://leetcode.com/problems/word-break/) | [youtube](https://www.youtube.com/watch?v=Sx9NNgInc3A)

Given a dictionary of words and an input string tell whether the input string can be completely segmented into dictionary words.

<!-- 
```
Hint: ???
``` 
-->

---

### Find all Palindrome Substrings

```Topic: Strings | Leetcode: Medium 🧡```

Given a string find all non-single letter substrings that are palindromes.

[leetcode](https://leetcode.com/problems/palindromic-substrings/) | [youtube](https://www.youtube.com/watch?v=4RACzI5-du8)

<!--
```
Hint: ???
```
-->


---

### Largest Sum Subarray

```Topic: Dynamic Programming | Leetcode: Easy 💚```

Given an array, find the contiguous subarray with the largest sum.

[leetcode](https://leetcode.com/problems/maximum-subarray/) | [youtube](https://www.youtube.com/watch?v=5WZl3MMT0Eg)

<!--
```
Hint: ???
```
-->

---

### Determine if the Number is Valid

```Topic: Dynamic Programming | Leetcode: Hard 💔```

Given an input string, determine if it makes a valid number or not. For simplicity, assume that white spaces are not present in the input.

[leetcode](https://leetcode.com/problems/valid-number/) | [youtube](https://www.youtube.com/watch?v=-6H2UFV68RI)

<!--
```
Hint: ???
```
-->

---

### Print balanced brace combinations

```Topic: Backtracking | Leetcode: Medium 🧡```

Print all braces combinations for a given value 'N' so that they are balanced.

[leetcode](https://leetcode.com/problems/generate-parentheses/) | [youtube](https://www.youtube.com/watch?v=s9fokUqJ76A)

```
Hint: Make a shared return array and count integers for opening and closing prenetheses count then recurse down to a base case related to the counts and n. Kinda remember it but might be missing something?
```

---

### Minimum Spanning Tree

```Topic: Graphs | Leetcode: Medium 🧡```

Find the minimum spanning tree of a connected, undirected graph with weighted edges.

[leetcode (multiples)](https://leetcode.com/tag/minimum-spanning-tree/) 

[leetcode](https://www.youtube.com/watch?v=f7JOBJIC-NA)| [youtube](https://www.youtube.com/watch?v=f7JOBJIC-NA)

<!--
```
Hint: ???
```
-->

---

### Implement a LRU Cache

```Topic: Design | Leetcode: Medium 🧡```

Least Recently Used (LRU) is a common caching strategy. It defines the policy to evict elements from the cache to make room for new elements when the cache is full, meaning it discards the least recently used items first.

[leetcode](https://leetcode.com/problems/lru-cache/) | [youtube](https://www.youtube.com/watch?v=7ABFKPK2hD4)

```
Hint: Use a linked list representing a queue and a hashmap for looking up nodes.
```

---

### Find the High and Low Index

```Topic: Searching & Sorting | Leetcode: Medium 🧡```

Given a sorted array of integers, return the low and high index of the given key. Return -1 if not found. The array length can be in the millions with many duplicates.

[leetcode](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | [youtube](https://www.youtube.com/watch?v=4sQL7R5ySUU)

<!--
```
Hint: ???
```
-->

---

### Merge Overlapping Intervals

```Topic: Searching & Sorting | Leetcode: Medium 🧡```

You are given an array (list) of interval pairs as input where each interval has a start and end timestamp. The input array is sorted by starting timestamps. You are required to merge overlapping intervals and return output array (list).

[leetcode](https://leetcode.com/problems/merge-intervals/) | [youtube](https://www.youtube.com/watch?v=44H3cEC2fFM)

```
Hint: Use sort and a new return array.
```

<!-- Sort it and make a new merged array to push into. -->
