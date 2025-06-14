# Missionaries-and-Cannibals-problem


🧩 Missionaries and Cannibals Problem – Description

The **Missionaries and Cannibals Problem** is a classic example of a problem in artificial intelligence and logic puzzle solving. It involves transporting a group of missionaries and cannibals across a river with certain constraints.

📝 Problem Statement

Three missionaries and three cannibals are on one side of a river. They all need to cross to the other side using a **boat that can carry only one or two people** at a time.

The challenge is to ensure that **at no point do the cannibals outnumber the missionaries** on either side of the river — if they do, the cannibals will eat the missionaries.

 ⚠️ Constraints

* The boat can carry **at most two people** at a time.
* The boat **cannot cross the river by itself**; at least one person must be on the boat to operate it.
* At any time, on either riverbank, the number of missionaries must be **equal to or more than** the number of cannibals (unless there are no missionaries on that side).
* All six individuals (3 missionaries and 3 cannibals) must reach the other side **safely**.

✅ Objective

Devise a **sequence of boat crossings** that successfully transports all missionaries and cannibals to the other side of the river **without violating the constraints**.

### 💡 Key Concepts Used

* **State space representation** (e.g., `(M, C, B)` format, where `M` is number of missionaries, `C` is number of cannibals, and `B` indicates the boat's position)
* **Search algorithms** like BFS, DFS, or A\* to find the valid sequence
* **Backtracking** to explore multiple paths and avoid dead ends
* **State validation** to ensure rules are not broken at each step

