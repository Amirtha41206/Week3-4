## Week 3–4: Sorting & Searching Algorithms (Java)

## Overview
This repository contains implementations of fundamental sorting and searching algorithms applied to real-world financial scenarios such as transaction processing, risk analysis, and portfolio management.

---

## Objectives
- Implement classical algorithms in practical use cases
- Analyze time and space complexity
- Understand stability and efficiency trade-offs
- Apply algorithms to finance-based datasets

---

## Problems Covered

### Problem 1: Transaction Fee Sorting
- Bubble Sort (ascending by fee)
- Insertion Sort (fee + timestamp)
- Stable sorting
- Outlier detection (> $50)

### Problem 2: Client Risk Ranking
- Bubble Sort (ascending risk score)
- Insertion Sort (descending risk + balance)
- Top-K highest risk clients

### Problem 3: Trade Volume Analysis
- Merge Sort (ascending, stable)
- Quick Sort (descending)
- Merge two sorted arrays
- Total volume calculation

### Problem 4: Portfolio Return Sorting
- Merge Sort (ascending returns)
- Quick Sort (descending returns + volatility)
- Median-of-3 pivot selection
- Hybrid Quick + Insertion optimization

### Problem 5: Account ID Lookup
- Linear Search (first & last occurrence)
- Binary Search (sorted data)
- Count duplicate occurrences
- Comparison tracking

### Problem 6: Risk Threshold Lookup
- Linear Search (unsorted data)
- Binary Search (sorted data)
- Floor & Ceiling values
- Insertion point (lower bound)

---

## Technologies Used
- Java
- Arrays and ArrayList
- Object-Oriented Programming

---

## Time Complexity Summary

| Algorithm        | Best Case | Worst Case |
|-----------------|----------|-----------|
| Bubble Sort      | O(n)     | O(n²)     |
| Insertion Sort   | O(n)     | O(n²)     |
| Merge Sort       | O(n log n) | O(n log n) |
| Quick Sort       | O(n log n) | O(n²)     |
| Linear Search    | O(1)     | O(n)      |
| Binary Search    | O(1)     | O(log n)  |

---

## How to Run
1. Clone the repository:
   git clone <your-repo-url>

2. Navigate to the folder:
   cd Week3-4

3. Compile:
   javac *.java

4. Run:
   java ClassName

---

##  Use Cases
- Banking transaction audits
- Risk management systems
- Portfolio optimization
- Fraud detection and compliance
- Financial data analytics

---

## Author
- Name: Amirtha S S
- Course: CSE (AI & ML)
- Institution: SRM Institute of Science and Technology

---

## Conclusion
This project demonstrates how classical algorithms can be effectively applied to real-world financial systems, highlighting their performance, stability, and scalability.