
# 🧠 Comparative Evaluations of Pathfinding Techniques in Undirected Graphs

### 📚 Project 3 of 6 – Academic Research Paper | University of North Texas

This project explores the comparative evaluation of several pathfinding algorithms within undirected graphs through both theoretical analysis and simulation-based experimentation. Developed as part of an academic research initiative, this project delivers a detailed study on the effectiveness of Dijkstra’s Algorithm, A* Search, Ant Colony Optimization (ACO), and Breadth-First Search (BFS) when applied to complex real-world navigation scenarios.

The work is presented in a formal IEEE-style report and serves as a reference point for further research into algorithmic efficiency and optimization strategies in graph theory.

---

## 📖 Abstract Summary

In this research, we examine the computational behavior and problem-solving capabilities of prominent pathfinding algorithms. The goal is to identify which algorithms are best suited for navigation in undirected graph environments, which are frequently encountered in fields such as robotics, AI, and network routing.

We conducted a performance-oriented survey of classic approaches like Dijkstra and BFS, alongside modern and bio-inspired techniques such as A* and ACO. The study explores real-time routing capabilities, execution efficiency, algorithmic complexity, and performance bottlenecks.

---

## 🧠 Research Objectives

- Perform a comparative analysis of Dijkstra, BFS, A*, and ACO in undirected graph environments.
- Evaluate computational efficiency, memory usage, execution time, and path optimality.
- Highlight key innovations such as randomized SSSP approaches and linear algebra-based BFS optimization.
- Visualize algorithm behavior across different input scenarios and complexity conditions.
- Offer insights into practical trade-offs and real-world application viability.

---

## 📊 Algorithms Reviewed

### 🔹 Dijkstra’s Algorithm
A deterministic graph traversal strategy used to find the shortest path from a source node to all others. Ideal for graphs with non-negative weights. The paper discusses improvements in its priority queue and data structure usage.

### 🔹 A* Search
A heuristic-based search technique that combines the cost to reach a node and an estimated cost to the goal. Weighted versions of A* are reviewed with use cases in UAV path planning and autonomous navigation.

### 🔹 Ant Colony Optimization (ACO)
A probabilistic metaheuristic inspired by ant behavior and pheromone communication. It is suited for dynamic environments and complex optimization tasks like scheduling and load balancing.

### 🔹 Breadth-First Search (BFS)
While simple and efficient for unweighted graphs, BFS is extended in our study through linear algebra methods. Sparse matrix representations and algebraic formulations enable scalable traversal in massive datasets.

---

## 📈 Comparative Evaluation

The performance of these algorithms was assessed based on:

- **Runtime complexity and speed**
- **Memory efficiency**
- **Path optimality and total distance traveled**
- **Number of visited nodes and heuristic precision**
- **Suitability for different data density and input size**

Results show A* delivers highly optimized results in structured environments, while ACO is more adaptive in open-ended or uncertain domains. Dijkstra’s algorithm performs consistently but lacks scalability in high-density graphs. BFS offers a strong baseline with rapid unweighted traversal but falls short for weighted applications.

---

## 🧪 Key Findings & Innovations

- A modified Dijkstra approach using Fibonacci heaps improves performance in large graphs.
- Linear algebraic BFS reformulation provides computational advantages for big data scenarios.
- ACO demonstrates superior adaptability and convergence in dynamic scheduling and resource planning.
- Randomized algorithms can outperform deterministic ones in certain time-constrained tasks.

---

## 📎 Use Cases and Applications

These algorithms are foundational in systems requiring:
- Real-time GPS navigation
- AI pathfinding in games and robotics
- Autonomous vehicle routing
- Network traffic flow and packet routing
- Complex scheduling and resource allocation

---

## 📄 Project Report

You can read the complete report in IEEE format below:
📄 [Comparative_Evaluations_Pathfinding.pdf](docs/Comparative_Evaluations_Pathfinding.pdf)

> *Note: This paper has not been officially published or submitted to IEEE and is for academic and demonstrative purposes only.*

---

## 👨‍🔬 Contributors

- Ganesh Gundekarla  
- Shreya Sri Bearelly  
- Divya Sree Dandu  
- Vikas Varala  
- Ashritha Bollam

---

## 🧠 References and Literature

The study references 16+ scholarly and IEEE sources, including foundational works by Dijkstra, Tarjan, Hopcroft & Ullman, and modern studies on ACO, UAV navigation, and particle swarm optimization.

---

## 🏁 Conclusion

This project illustrates the evolving nature of graph theory algorithms in real-world computing. Through in-depth evaluation and exploration of classical and modern methods, we provide a roadmap for selecting the most efficient algorithm based on context, scalability, and performance goals. It reinforces the value of interdisciplinary research—merging computational logic, biological heuristics, and linear algebra for smarter algorithm design.

---

## 📫 Get in Touch

Developed as part of the graduate coursework at the University of North Texas by Ganesh Gundekarla.  
📬 [LinkedIn](https://www.linkedin.com/in/ganeshgundekarla) • [GitHub](https://github.com/gnevercodes)

