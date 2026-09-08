# 🚀 Data Structures and Algorithms (DSA) Practice in C++

Welcome to my **DSA Practice Repository**! This repository is dedicated to mastering Data Structures and Algorithms by implementing them from scratch using the **C programming language**. 

The goal of this project is to strengthen problem-solving skills, understand low-level memory management (pointers, dynamic memory allocation), and prepare for technical coding interviews.

---

## 📂 Repository Structure

The repository is organized by topic. Each directory contains the source code (`.c` files) along with explanations or problem statements where applicable.

```text
├── Data-Structures/
│   ├── Arrays/
│   ├── Linked-Lists/
│   │   ├── singly_linked_list.cpp
│   │   └── doubly_linked_list.cpp
│   ├── Stacks/
│   ├── Queues/
│   ├── Trees/
│   │   └── binary_search_tree.cpp
│   └── Graphs/
├── Algorithms/
│   ├── Searching/
│   │   ├── binary_search.cpp
│   │   └── linear_search.cpp
│   ├── Sorting/
│   │   ├── bubble_sort.cpp
│   │   ├── quick_sort.cpp
│   │   └── merge_sort.cpp
│   ├── Recursion/
│   └── Dynamic-Programming/
└── LeetCode-Solutions/
```

---

## 🛠️ Tech Stack & Prerequisites

* **Language:** Cpp (C11 standard preferred)
* **Compiler:** `gcc` (GNU Compiler Collection) or `clang`
* **Operating System:** Works across Windows (MinGW/WSL), macOS, and Linux

### Installation (For local compilation)
Ensure you have a Cpp compiler installed. Check your installation by running:
```bash
gcc --version
```

---

## 🚀 How to Run the Code

To compile and run any specific Cpp file, follow these steps using your terminal:

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd YOUR_REPOSITORY_NAME
   ```

2. **Navigate to the target directory:**
   ```bash
   cd Algorithms/Sorting
   ```

3. **Compile the program:**
   ```bash
   gcc -o quick_sort quick_sort.c
   ```

4. **Execute the binary:**
   ```bash
   ./quick_sort
   ```

---

## 📈 Progress Tracker

Here is a snapshot of topics planned and completed:

### Data Structures
- [x] Arrays (Static & Dynamic)
- [x] Linked Lists (Singly, Doubly, Circular)
- [ ] Stacks & Queues (Array & Linked List implementations)
- [ ] Binary Trees & Binary Search Trees (BST)
- [ ] AVL Trees / Heaps
- [ ] Graphs (Adjacency Matrix & List representation)

### Algorithms
- [x] Linear & Binary Search
- [x] Bubble, Insertion, & Selection Sort
- [x] Merge Sort & Quick Sort
- [ ] Breadth-First Search (BFS) & Depth-First Search (DFS)
- [ ] Dijkstra's Shortest Path Algorithm
- [ ] Basic Dynamic Programming (Fibonacci, Knapsack)

---

## 💡 Key Learnings & Implementations

* **Memory Management:** Extensive use of `malloc()`, `calloc()`, `realloc()`, and `free()` to prevent memory leaks.
* **Pointers:** Deep dive into pointer arithmetic, passing pointers to functions, and double pointers (`**`) for dynamic structures like trees and graphs.
* **Time & Space Complexity:** Analyzing Big-O notations for every algorithm written to optimize efficiency.

---

## 🤝 Contributing

This is a personal practice repo, but feel free to fork it, report bugs, or suggest optimizations via Pull Requests! 

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

