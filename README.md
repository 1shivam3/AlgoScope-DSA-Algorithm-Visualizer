# AlgoLens - Interactive Data Structures and Algorithms Visualizer

An interactive web application designed to demonstrate the mechanics and theoretical performance of fundamental sorting, searching, and pathfinding algorithms. Built for academic evaluation and practical demonstration.


## Author Information

- Student Name: Shivam Kumar
- Roll Number: 11252640
- Section: 3B2


## Project Overview

AlgoLens provides real-time, visual execution of classic computer science algorithms. The platform illustrates state transitions, pointer movements, and recursive partitioning through color-coded updates and real-time operational telemetry.


## Features and Implemented Algorithms

### 1. Sorting Algorithms
- Algorithms: Bubble Sort, Selection Sort, Insertion Sort, Quick Sort, Merge Sort.
- Real-Time Telemetry: Live counters for comparison counts, element swaps, and memory-array accesses.
- Controls: Dynamic array size scaling, execution speed regulation, and random array regeneration.

### 2. Searching Algorithms
- Algorithms: Linear Search, Binary Search (with automatic array sorting).
- Diagnostics: Visual tracking of search bounds (left, middle, right pointers) and step-by-step element evaluation.

### 3. Graph Pathfinding and Grid Traversal
- Algorithms: Dijkstra's Algorithm, Breadth-First Search (BFS), Depth-First Search (DFS).
- Weighted Grid Simulation: Support for weighted nodes (cost = 5) alongside standard traversable cells and non-traversable walls.
- Comparative Analysis: Demonstrates the mathematical divergence between BFS (hop-count minimization) and Dijkstra's algorithm (total path-cost minimization).
- Environment Generation: Interactive wall and weight drawing tools, plus an automated maze generation routine.

### 4. Theoretical Complexity Panel
- Contextual reference drawer displaying Best, Average, and Worst Case Time Complexities along with Space Complexity bounds for each implemented algorithm.


## Technology Stack

- Markup: HTML5
- Styling: Tailwind CSS
- Scripting: Vanilla JavaScript (ES6+)
- Concurrency: Asynchronous step execution using native Promises and async/await


## Installation and Local Execution

This project is completely client-side and requires no external package managers, runtimes, or build steps.

1. Clone the repository:
   git clone [https://github.com/1shivam3/AlgoScope-DSA-Algorithm-Visualizer]

2. Navigate to the project directory:
   cd AlgoScope-DSA-Algorithm-Visualizer

3. Open the application:
   Open index.html in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari).


## License

This project is developed for educational and academic evaluation purposes.
