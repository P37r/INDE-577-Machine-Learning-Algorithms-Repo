# Maximum Clique (Integer Programming Formulation)

---

## Overview

**Maximum Clique Problem** is a classic NP-hard problem in graph theory. A *clique* is a subset of vertices in an undirected graph such that every two distinct vertices are adjacent. The **Maximum Clique** problem seeks the largest such subset.

This implementation solves the problem using **Integer Programming (IP)** via the `PuLP` library in Python.

### Key Concepts

- **Clique:** A subset of nodes all connected to each other.
- **Maximum Clique:** The largest such subset in a given graph.
- **Integer Programming:** Optimization method where variables are constrained to be integers (binary in this case).

---

## Objective

**Task:** Given an undirected graph, find the largest set of nodes such that every pair of nodes is connected — the **maximum clique**.

---

## Integer Program Formulation

Let $G = (V, E)$ be an undirected graph with vertex set $V$ and edge set $E$.

**Decision Variables:**

Let  
$$
x_i = \text{1 if node } i \text{ is in the clique, 0 otherwise}
$$

**Objective Function:**

$$
\text{Maximize} \quad \sum_{i \in V} x_i
$$

**Constraints:**

$$
x_i + x_j \leq 1 \quad \forall \{i, j\} \notin E
$$

This ensures that no two non-adjacent nodes are both included in the clique.

---

## Dataset / Graph Input

- The graph can be created manually or imported via `networkx`.
- Nodes and edges should define an undirected graph.

---

## Tools and Libraries

- `networkx`  
- `pulp`  
- `matplotlib`  

---
