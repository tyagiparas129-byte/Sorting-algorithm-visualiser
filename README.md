# Sorting Algorithm Visualizer

**Name:** Paras Tyagi  
**UID:** 25BDA70065  
**Course:** ADS Lab Project

An interactive web app for an Algorithms and Data Structures (ADS) lab project. Four sorting algorithms sort the same random array side by side, so you can see how their strategies differ.

## Features

- Bubble Sort, Selection Sort, Insertion Sort and Quick Sort
- Adjustable array size (10 to 150) and animation speed
- Live comparison and swap counts for each algorithm
- Amber bars show elements being compared, red bars show elements being swapped
- Performance table and execution-time chart for the same input array
- Works in light and dark mode, and on phones

## How to run

Open `index.html` in any modern browser. No installation or build step is needed.

## Algorithms and complexity

| Algorithm      | Best case  | Average case | Worst case | Space    |
|----------------|------------|--------------|------------|----------|
| Bubble Sort    | O(n)       | O(n²)        | O(n²)      | O(1)     |
| Selection Sort | O(n²)      | O(n²)        | O(n²)      | O(1)     |
| Insertion Sort | O(n)       | O(n²)        | O(n²)      | O(1)     |
| Quick Sort     | O(n log n) | O(n log n)   | O(n²)      | O(log n) |

## How it works

Each algorithm is written as a JavaScript generator that sorts an array and reports every comparison and swap as it happens. The page runs all four generators in step, so they advance by the same number of operations per frame. Final timings come from running each algorithm repeatedly on the same array and averaging the result.

## Tech

HTML, CSS and JavaScript in a single file. Bars are drawn on a canvas.
