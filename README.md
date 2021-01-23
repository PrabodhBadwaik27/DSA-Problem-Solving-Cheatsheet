# DSA Problem Solving Cheatsheet
*[Currently in Making]*  
This repository is for the quick overview of important Data Structures and Algorithms concepts.  
**Pre-requisite:** Ability to run basic programs like patterns.  
**Expertise:** BEGINNER, INTERMEDIATE  

*NOTE: This is not a complete programming guide but more specifically designed for BEGINNER/INTERMEDIATE level programmers only to help them overlook very important concepts related to Data Structures and Algorithms before interviews or for periodic reviews.*  

Concepts Included:  
## 1. Data Structures
    1. Arrays  
    2. Hashtables
    3. Linked List  
    4. Queue  
    5. Stack  
    6. Tree  
    7. Trie  
    8. Graph  
 
## 2. Sorting Algorithms  
    1. Bubble Sort  
    2. Selection Sort  
    3. Insertion Sort  
    4. Merge Sort  
    5. Quick Sort  
    6. Heap Sort  
    7. Counting Sort  
    8. Radix Sort  

# 1. Data Structures

## 1.1 Arrays

#### Static Array 
|Operation|Complexity|
|---|---|
|Insert|O(n)|  
|Delete|O(n)|  
|Lookup|O(1)|  
|Append|O(1)|  

#### Dynamic Array  
|Operation|Complexity|
|---|---|
|Insert|O(n)|  
|Delete|O(n)|  
|Lookup|O(1)|
|Append|O(1)\*|  
  
\*O(n) in case of reallocation of memory *(while other languages handles memory allocation by themselves, C has realloc() function)*


#### String Question
Convert String to Array 
|Language|Function|
|---|---|
|C#, Java|.toCharArray()|
|Python|.list()|  
|JavaScript|split()|  
|C|indexing\*|  
  
\*A string is by-default stored as an array of characters. Hence its characters can be directly accessed by indexing.

#### Searching
Is array sorted?  
  - If **Yes**, Binary Search : O(logN)
  - IF **No**
    - Will Sorting make solution efficient?   
      - If **Yes**, Sorting Algorithms
      - If **No**, Linear Search : O(n)
