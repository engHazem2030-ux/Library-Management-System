# 📚 C++ Library Management System (Data Structures & Algorithms)

A robust console-based Library Management System developed in C++. This project demonstrates core computer science fundamentals by implementing a custom Singly Linked List** data structure from scratch for dynamic memory management, paired with fundamental searching and sorting algorithms.

## ⚡ Core Features & Operations

* Dynamic Book Inventory: Add, display, and delete books dynamically using linked nodes with manual pointer management.
* Efficient Record Lookup Linear search implementation to look up book records by unique identifier (`ID`).
* Publication Year Sorting: Custom sorting algorithm (`Selection Sort` logic) to organize book collections chronologically.
* Borrowing & Return Lifecycle: State-driven book availability tracking with real-time status updates.
* Encapsulation & OOP: Separation of concerns using `Book` and `Library` classes with clear access modifiers.

## 🛠️ Data Structures & Algorithms Applied

* Data Structure: Singly Linked List (`node* head`) for dynamic $O(1)$ insertions and linear deletions.
* Algorithm (Sorting): In-place swap-based selection sort over linked nodes ($O(n^2)$ time complexity).
* Algorithm (Searching): Sequential traversal search algorithm ($O(n)$ time complexity).
* Memory Management: Dynamic allocation and deallocation (`new` / `delete`) avoiding memory leaks.

## 💻 Compilation & Execution

Clone and compile using any standard C++ compiler (GCC / Clang / MSVC):

```bash
# Clone the repository
git clone [https://github.com/engHazem2030-ux/Library-Management-System.git](https://github.com/engHazem2030-ux/Library-Management-System.git)

# Compile the source code
g++ -std=c++17 project1.c++.c++ -o library_system

# Run the executable
./library_system
