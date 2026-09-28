# DSA Practice: Beginner → Advanced

A hands-on collection of **Data Structures & Algorithms practice in Python**, built as a learning and interview-preparation repository.

The goal is to understand the fundamentals, implement solutions from scratch, compare different approaches, analyze complexity, and gradually move from brute-force thinking to more efficient problem-solving patterns.

> **Status:** 🚧 Work in Progress
>
> New problems and topics will be added as the practice journey continues.

## 📌 Problems Solved

The main notebook currently contains practice problems across **Number Theory, Hashing, Recursion, Arrays, Searching, Sorting, Matrices, and common interview problem-solving patterns**.

### 🔢 Number & Basic Problem Solving

- Extract the digits of a number
- Count the number of digits
- Check whether a number is a palindrome
- Check whether a number is an Armstrong number
- Print all factors of a number

### #️⃣ Hashing & Frequency Mapping

- Build a frequency map for elements in an array
- Count elements of one list that occur in another list
- Character hashing and frequency counting
- Compare brute-force hashing approaches with dictionary-based approaches
- Understand array hashing using constrained value ranges and ASCII-based hashing

### 🔁 Recursion

- Print a value multiple times using recursion
- Understand **head recursion** and **tail recursion**
- Print a value `N` times using recursion and parameters
- Print numbers from `1` to `N` using different recursive approaches
- Calculate the sum of `1` to `N` using parameterized recursion
- Calculate the sum of `1` to `N` using functional recursion
- Calculate factorial using functional recursion
- Calculate factorial using parameterized recursion
- Reverse part of an array using recursion and two pointers
- Understand recursion, base cases, recursion flow, stack space, and backtracking

### 📦 Arrays

- Reverse an array
- Reverse an array using two pointers
- Find the largest element in an array
- Find the second-largest element
- Check whether an array is sorted
- Remove duplicates from an array
- Right rotate an array by one position
- Right rotate an array by `K` positions
- Move all zeroes to the end while maintaining the order of non-zero elements
- Find the missing number in an array
- Find the maximum number of consecutive ones
- Solve the Two Sum problem
- Find the maximum subarray sum
- Solve the Best Time to Buy and Sell Stock problem
- Rearrange array elements by sign
- Find the longest consecutive subsequence

### 🔎 Searching

- Linear search
- Compare dictionary-based lookup with straightforward linear traversal

### 🔃 Sorting

- Selection Sort
- Bubble Sort
- Insertion Sort
- Merge Sort
- Quick Sort
- Compare sorting approaches and their time/space complexity

### ➕ 3Sum & 4Sum

- **3Sum:** Find triplets whose sum is `0`
  - Brute force
  - Optimized nested-loop approach
  - Set-based approach
  - Two-pointer optimized approach
- **4Sum:** Find quadruplets whose sum is `0`
  - Brute force
  - Set-based optimization

### 🔲 Matrices

- Understand 2-D matrices / nested lists
- Determine matrix dimensions
- Iterate through a matrix
- Calculate the sum of matrix elements
- Print the upper triangle of a matrix
- Print the main diagonal
- Print the inverse diagonal
- Transpose a matrix
- Transpose a non-square matrix using a structured approach
- Set Matrix Zeroes
- Rotate a matrix by `90°`
- Print a matrix in spiral order

### 🔀 Array Merging

- Merge two sorted arrays
- Merge using Python's built-in sorting
- Merge and remove duplicates
- Merge using the merge-sort concept
- Merge using two pointers

### 📈 Dynamic / Pattern-Based Problems

- Fibonacci number at a given index
- Maximum subarray sum using **Kadane's Algorithm**
- Stock buy/sell profit using a single-pass approach
- Array rotation using the reversal technique
- 3Sum and 4Sum problem-solving patterns
- Matrix traversal, transformation, and rotation patterns

## 🧠 Approach Comparison

A major focus of this repository is not simply solving a problem once, but understanding how different approaches behave.

For several questions, multiple implementations are explored:

```text
Brute Force
     ↓
Improved Approach
     ↓
Optimize Time Complexity
     ↓
Optimize Space Complexity
     ↓
Understand the Trade-offs
```

Examples include:

| Problem | Approaches Explored |
|---|---|
| Counting digits | Loop, list-based approach, `log10` |
| Armstrong number | List-based, accumulator-based |
| Factors | Brute force, `sqrt(n)` approach |
| Frequency counting | Nested loops, frequency array, dictionary |
| Character hashing | Brute force, dictionary, ASCII indexing |
| Array reversal | Extra list, two pointers, recursion |
| String palindrome | Slicing, loop, two pointers, comparison, recursion |
| Fibonacci | Iterative array, recursion |
| Sorting | Selection, Bubble, Insertion, Merge, Quick Sort |
| Second largest | Sorting, two-pass, single-pass |
| Remove duplicates | Brute force, frequency mapping, two pointers |
| Array rotation | Indexing, repeated rotation, slicing, reversal |
| Move zeroes | Extra list, in-place approaches, single pass |
| Missing number | Brute force, frequency mapping, sum comparison |
| Two Sum | Hash map, brute force |
| Maximum subarray | Brute force, optimized nested loop, Kadane's Algorithm |
| Stock profit | Brute force, optimized nested loop, single pass |
| Merge sorted arrays | Sorting, merge-sort concept, two pointers |
| Rearrange by sign | Brute force, improved, two-pointer approaches |
| Longest consecutive sequence | Brute force, sorting, set |
| Matrix transpose | In-place square matrix, structured non-square approach |
| Set Matrix Zeroes | Brute force, row/column tracking |
| Rotate Matrix | Extra matrix, transpose + reverse |
| 3Sum | Brute force, optimized loops, sets, two pointers |
| 4Sum | Brute force, set-based optimization |

## ⏱️ Complexity Analysis

Time and space complexity are documented throughout the notebook wherever different approaches are compared.

Some of the complexity patterns explored include:

- `O(1)` constant-time operations
- `O(n)` linear traversal
- `O(log n)` / logarithmic-style operations
- `O(n log n)` sorting and divide-and-conquer patterns
- `O(n²)` nested-loop approaches
- `O(n³)` brute-force subarray approaches
- Recursive stack-space analysis

The purpose is to build the habit of asking:

> **Can this solution be made faster or use less memory?**

## 📚 Current DSA Roadmap

```text
✅ Number Basics
✅ Hashing
✅ Recursion Fundamentals
✅ Arrays
✅ Searching
✅ Sorting
✅ Matrix Basics & Problems
✅ Two-Pointer Techniques
✅ 3Sum / 4Sum
🚧 Binary Search
🚧 Linked Lists
🚧 Stack & Queue
🚧 Strings - Advanced Patterns
🚧 Trees & Binary Search Trees
🚧 Heaps & Priority Queues
🚧 Graphs
🚧 Greedy Algorithms
🚧 Backtracking
🚧 Dynamic Programming
🚧 Advanced DSA Patterns
```

## 📂 Repository Structure

```text
DSA-practice-beginner-advanced/
│
├── DSA Practice.ipynb      # Main DSA practice notebook
├── rough.ipynb              # Scratch work / experimentation
├── README.md                # Repository documentation
└── .ipynb_checkpoints/      # Jupyter-generated checkpoints
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/AyAnand117/DSA-practice-beginner-advanced.git
cd DSA-practice-beginner-advanced
```

### 2. Install Jupyter

```bash
pip install notebook
```

### 3. Launch the notebook

```bash
jupyter notebook
```

Open **`DSA Practice.ipynb`** and run the cells to explore the problems and solutions.

## 🛠️ Tech Stack

- **Python 3.9**
- **Jupyter Notebook**
- Python Standard Library

## 🔗 Practice Profile

- [LeetCode](https://leetcode.com/u/ay_an117/)

## 🎯 Learning Goals

This repository is being built around four principles:

**Solve → Analyze → Optimize → Practice**

The aim is to develop strong fundamentals rather than simply memorizing solutions. Each new problem is an opportunity to understand the underlying pattern, identify alternative approaches, and reason about their complexity.

## 🤝 Contributions

This is primarily a personal DSA learning repository, but suggestions, corrections, alternative solutions, and improvements are welcome.

Feel free to open an issue or submit a pull request with a better approach or explanation.

## ⭐ About

This repository is part of my ongoing effort to strengthen **Python, DSA, algorithmic thinking, and technical interview problem-solving skills**.

---

**Keep solving. Keep analyzing. Keep optimizing.**