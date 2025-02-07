# GatorLibrary: A Library Management System

GatorLibrary is a Python-based library management system that uses a Red-Black Tree for efficient book storage and retrieval and a MinHeap for managing reservations. This system provides functionalities to manage books, borrow/return operations, reservations, and more.

---

## Features

1. **Book Management:**
   - Insert new books into the library.
   - Delete books, including managing reservations and notifying patrons.
   - Search for books by ID or within a range.

2. **Borrowing and Returning:**
   - Borrow books if available; otherwise, reserve them in a priority queue.
   - Return books and allocate them to the next patron in the reservation queue if applicable.

3. **Reservation System:**
   - Manage a priority-based reservation system using a MinHeap.

4. **Utility Functions:**
   - Print details of a specific book.
   - Print all books within a specified ID range.
   - Find the closest book(s) to a given ID.
   - Count the number of color flips in the Red-Black Tree.

---

## Prerequisites

- Python 3.8 or above
- Modules:
  - `redblacktree`: Contains the `RedBlackTree`, `Node`, and `Book` classes.
  - `binaryminheap`: Contains the `MinHeap` class.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/username/gatorlibrary.git
   cd gatorlibrary
