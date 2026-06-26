# Quick Sort Visualizer

An interactive, single-file web app that visualizes the **Quick Sort** algorithm step by step. Watch how the array is partitioned around a pivot, follow the recursion as it unfolds, and read the matching pseudocode as each operation runs.

## Features

- **Animated sorting** — see comparisons and swaps highlighted in real time as the array gets sorted.
- **Pivot & partition view** — the active pivot and partition boundaries are color-coded so the strategy is easy to follow.
- **Lomuto & Hoare schemes** — explore the two classic partitioning approaches.
- **Recursion tree** — a live tree shows how Quick Sort breaks the array into sub-problems.
- **Pseudocode panel** — the current line of pseudocode is highlighted alongside the animation.
- **Multiple inputs** — generate _Random_, _Nearly sorted_, _Reversed_, or _Few unique_ arrays to compare behavior.
- **Playback controls** — Play, Step through one operation at a time, Reset, and adjust the speed.
- **Keyboard shortcuts** — `Space` to play/pause, `→` to step, `R` to reset.

## Usage

No build step or dependencies required. Just open the file in any modern browser:

```bash
open quicksort-visualizer.html
```

Or double-click `quicksort-visualizer.html` in your file manager.

## About

Quick Sort is a divide-and-conquer sorting algorithm with an average time complexity of **O(n log n)** (worst case **O(n²)**). This visualizer is a learning tool to build intuition for how the algorithm chooses a pivot, partitions the array, and recurses on the resulting halves.
