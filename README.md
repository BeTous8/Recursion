# Recursion Exercises

This repository contains my solutions to **The Odin Project's** recursion assignments, implementing both Fibonacci sequence generators and a merge sort algorithm.

## 📁 Files

- **`fibonacci.html`** - Iterative Fibonacci implementation
- **`merge-sort.html`** - Recursive merge sort algorithm

## 🎯 What's Implemented

### Fibonacci Sequence
- **Iterative approach**: Uses a for loop to build the sequence
- **Recursive approach**: Uses the helper function pattern for clean recursion
- Both functions take a number `n` and return an array of the first `n` Fibonacci numbers

**Example:**
```javascript
fibs(8) // Returns: [0, 1, 1, 2, 3, 5, 8, 13]
```

### Merge Sort
- **Recursive divide-and-conquer algorithm**
- Splits arrays in half until reaching single elements
- Merges sorted subarrays back together
- Handles arrays of any length including edge cases

**Example:**
```javascript
mergeSort([3, 2, 1, 13, 8, 5, 0, 1]) 
// Returns: [0, 1, 1, 2, 3, 5, 8, 13]
```

## 🚀 How to Run

1. Clone this repository
2. Open the HTML files in your browser
3. Check the browser console (F12) to see the output

## 🧠 Key Concepts Learned

- **Recursion fundamentals**: Base cases and recursive calls
- **Helper function pattern**: Clean public interfaces with recursive helpers
- **Call stack understanding**: How variables persist across recursive calls
- **Divide and conquer**: Breaking complex problems into simpler subproblems
- **Merge algorithm**: Combining sorted arrays efficiently

## 🔗 Context

Part of [The Odin Project](https://www.theodinproject.com/) curriculum - JavaScript course, recursion section.

---

*"The best way to understand recursion is to understand recursion."* 🔄