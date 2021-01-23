# DSA Problem Solving Cheatsheet
[Currently in Making]  
This repository is for the quick overview of important Data Structures and Algorithms concepts.  
**Pre-requisite:** Ability to run basic programs like patterns.  
**Expertise:** BEGINNER, INTERMEDIATE  

*NOTE: This is not a complete programming guide but more specifically designed for BEGINNER/INTERMEDIATE level programmers only to help them overlook very important concepts related to Data Structures and Algorithms before interviews or for periodic reviews.*  

Concepts Included:  
## 1. Data Structures
i) Arrays  
ii) Hashtables  
iii) Linked List  
iv) Queue  
v) Stack  
vi) Tree  
vii) Trie  
viii) Graph  
 
## 2. Sorting Algorithms  
i) Bubble Sort  
ii) Selection Sort  
iii) Insertion Sort  
iv) Merge Sort  
v) Quick Sort  
vi) Heap Sort  
vii) Counting Sort  
viii) Radix Sort  

# 1. Data Structures

## 1.1 Arrays

#### Static Array    
Insert - O(n)  
Delete - O(n)  
Lookup - O(1)  
Append - O(1)  

#### Dynamic Array  
Insert - O(n)  
Delete - O(n)  
Lookup - O(1)  
Append - O(1)* : O(n) in case of reallocation of memory *(while other languages handles memory allocation by themselves, C has realloc() function)*  


#### String Question
Convert String to Array  
C#, Java   - toCharArray()  
Python     - list()  
JavaScript - split()  
*C         - A string is by-default stored as an array of characters. Hence its characters can be directly accessed by indexing.

#### Searching
Is array sorted?  
  - If **Yes**, Binary Search : O(logN)
  - IF **No**
    - Will Sorting make solution efficient?   
      - If **Yes**, Sorting Algorithms
      - If **No**, Linear Search : O(n)
