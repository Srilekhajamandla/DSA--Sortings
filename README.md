# Sorting Algorithms in Python

This repository contains basic implementations of popular sorting algorithms using Python. The notebook demonstrates the logic, working process, and examples for understanding how sorting techniques operate internally.

## Project Overview

The project focuses on:

* Understanding sorting concepts
* Implementing sorting algorithms from scratch
* Practicing Python programming logic
* Improving problem-solving and algorithmic thinking

The notebook includes step-by-step implementations and examples for learning purposes.

---

# Algorithms Covered

## 1. Built-in Sorting

Python provides two built-in methods for sorting:

### `sort()`

* Sorts the original list directly
* Modifies the existing list
* Works in ascending order by default

Example:

```python
arr.sort()
```

### `sorted()`

* Returns a new sorted list
* Original list remains unchanged

Example:

```python
arr1 = sorted(arr)
```

---

# 2. Bubble Sort

Bubble Sort repeatedly compares adjacent elements and swaps them if they are in the wrong order.

## Logic

* Compare adjacent elements
* Swap if left element is greater than right element
* Repeat until the array becomes sorted

## Features

* Simple and beginner-friendly
* Uses multiple passes
* Largest element moves to the end after each pass

## Time Complexity

| Case    | Complexity |
| ------- | ---------- |
| Best    | O(n)       |
| Average | O(n²)      |
| Worst   | O(n²)      |

---

# 3. Selection Sort

Selection Sort repeatedly selects the minimum element from the unsorted part and places it in the correct position.

## Logic

* Find the minimum element
* Swap it with the current index
* Move to the next position

## Features

* Performs fewer swaps
* Easy to understand
* Good for learning sorting fundamentals

## Time Complexity

| Case    | Complexity |
| ------- | ---------- |
| Best    | O(n²)      |
| Average | O(n²)      |
| Worst   | O(n²)      |

---

# 4. Insertion Sort

Insertion Sort builds the sorted array one element at a time.

## Logic

* Pick one element
* Compare it with previous elements
* Insert it into the correct position

## Features

* Efficient for small datasets
* Stable sorting algorithm
* Works similarly to arranging playing cards

## Time Complexity

| Case    | Complexity |
| ------- | ---------- |
| Best    | O(n)       |
| Average | O(n²)      |
| Worst   | O(n²)      |

---

# Technologies Used

* Python
* Jupyter Notebook

---

# Learning Outcomes

By working on this project, you can:

* Understand sorting algorithm logic
* Improve Python coding skills
* Learn nested loops and swapping concepts
* Analyze time complexity
* Build a strong foundation for Data Structures and Algorithms (DSA)

---

# Repository Structure

```bash
Sortings.ipynb
README.md
```

---

# How to Run

1. Install Python
2. Install Jupyter Notebook
3. Open the notebook:

```bash
jupyter notebook
```

4. Run all cells step by step

---

# Future Improvements

* Add Merge Sort
* Add Quick Sort
* Add Heap Sort
* Add visualization for sorting steps
* Compare algorithm performance using execution time

---

# Conclusion

This project is designed to strengthen the fundamentals of sorting algorithms and Python programming. It is useful for beginners preparing for coding interviews, DSA practice, and technical assessments.
