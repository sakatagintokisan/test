# C++ Algorithms & Data Structures Curriculum

A structured 7‑week roadmap to mastering C++ STL, fundamental algorithms, and advanced data structures—complete with reading links, hands‑on code implementations, and assignments.

---

## Repository Structure

```plaintext
cpp-algo-curriculum/
├── syllabus/                   # Weekly topic outlines and resource links
│   └── syllabus.md             # Full syllabus in Markdown
├── implementations/            # Code solutions for key data structures
│   ├── 2d_prefix_sum.cpp       # 2D prefix-sum / submatrix sum implementation
│   ├── order_set_multiset.cpp  # PBDS order_set and multiset implementation
│   ├── segment_tree_iterative.cpp # Iterative segment tree implementation
│   └── sparse_table.cpp        # Sparse table implementation
├── assignments/                # Submitted assignment files
│   └── assignment1_submission/ # All files for Assignment 1 (deadline 17/06/2024)
├── LICENSE                     # (Optional) MIT license file
└── README.md                   # Project overview and usage instructions
```

---

## Syllabus Overview

All detailed weekly topics and practice links are in **syllabus/syllabus.md**. A quick glance:

- **Week 1**: Time Complexity, C++ STL Part 1, Bubble/Selection/Insertion/Merge/Quick Sort, Counting Inversions.
- **Week 2**: Reading C++ docs, Binary Search, STL maps/multisets, 1D & 2D Prefix Sums, Sparse Table, Linked Lists.
- **Week 3**: Stack, Queue, Priority Queue—each with implementations and example problems.
- **Week 4**: Trees and BSTs: traversals, height, diameter, insertion in BST.
- **Week 6**: Segment Trees—theory, implementations, Codeforces EDU practice.
- **Week 7**: Disjoint Set Union (DSU)—concepts, implementation, CF practice problems.
- **Fun Problems**: curated challenge set.
- **Assignments**: test assignment and Assignment 1 (links in `assignments/`).

---

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/cpp-algo-curriculum.git
   cd cpp-algo-curriculum
   ```

2. **Browse the Syllabus**

   - Open `syllabus/syllabus.md` in your editor to view all weekly topics and resource links.

3. **Review & Run Implementations**

   - Look in `implementations/` for ready-to-compile `.cpp` files. Each includes comments and example usage.

   ```bash
   # Example: compile and run 2D prefix sum
   g++ implementations/2d_prefix_sum.cpp -o prefix_sum
   ./prefix_sum
   ```

4. **Review Assignments**

   - Check `assignments/assignment1_submission/` for the completed Assignment 1 source files and write-ups.

---

## Contributing

Contributions are welcome! To propose edits or add resources:

1. Fork this repository on GitHub.
2. Create a new branch (`git checkout -b feature/awesome-topic`).
3. Commit your additions (`git commit -m "Add week8 advanced graphs"`).
4. Push to your fork & open a Pull Request.

---

## License

This work is licensed under the MIT License. See [LICENSE](LICENSE) for details.

