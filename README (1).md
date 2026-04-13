# 🚀 Memory Management Simulator

### 🔗 Data Structures Project using Linked List

\---

## 📖 Overview

This project simulates how an operating system manages memory using a **Linked List**. It demonstrates allocation, deallocation, fragmentation handling, and compaction techniques in a structured and visual way.

The simulator is implemented using **C programming** along with an **interactive HTML interface**.

\---

## 🎯 Objectives

* Understand memory allocation techniques
* Implement linked list-based memory representation
* Simulate real-world OS memory behavior
* Visualize fragmentation and optimization

\---

## ⚙️ Features

* 📦 First-Fit Memory Allocation
* 🔄 Memory Deallocation
* 🧩 Fragmentation Handling
* 🔗 Linked List Structure
* ⚡ Block Splitting \& Merging (Coalescing)
* 🖥️ Interactive Memory Visualization (HTML UI)

\---

## 🧠 Concepts Used

* Linked List (Singly Linked List)
* Dynamic Memory Allocation
* First-Fit Algorithm
* Internal \& External Fragmentation
* Memory Compaction
* Structures \& Pointers in C

\---

## 🏗️ Project Structure

```
Memory Management Simulator/
│
├── memory\_sim.c        # Core C implementation
├── DSA.html           # Interactive simulation UI
├── README.md          # Documentation
```

\---

## ⚡ How It Works

### 🔹 Memory Representation

* Memory is divided into blocks
* Each block is a node in a linked list
* Each node stores:

  * Size of block
  * Process ID
  * Allocation status
  * Pointer to next block

\---

### 🔹 Allocation (First-Fit)

1. Traverse memory from the beginning
2. Find the first free block large enough
3. Split block if needed
4. Assign memory to process

\---

### 🔹 Deallocation

1. Find block using Process ID
2. Mark it as free
3. Merge adjacent free blocks

\---

### 🔹 Compaction

* Rearranges memory blocks
* Combines all free memory into one block
* Reduces fragmentation

\---

## 💻 How to Run

### ▶️ Run C Program

```bash
gcc memory\_sim.c -o memory\_sim
./memory\_sim
```

\---

### 🌐 Run HTML Simulator

1. Open `DSA.html` in your browser
2. Use buttons to:

   * Allocate memory
   * Free memory
   * Compact memory
   * Reset simulation

\---

## 📊 Time Complexity

|Operation|Complexity|
|-|-|
|Allocation|O(n)|
|Deallocation|O(n)|
|Coalescing|O(1)|
|Compaction|O(n)|

\---

## ✅ Advantages

* Efficient memory usage
* Dynamic allocation
* Real-world OS simulation
* Easy to understand visualization

\---

## ⚠️ Limitations

* Only First-Fit implemented
* No backward merging (singly linked list)
* Not actual OS-level memory handling

\---

## 🔮 Future Improvements

* Implement Best-Fit \& Worst-Fit
* Use Doubly Linked List
* Add GUI (React / Java / Python)
* Add real-time graph visualization

\---

## 👨‍💻 Author

**Rakshit**  
BCA Data Science Student

\---

## 

