# Weekly Challenge 12: K-edge Shortest Paths in Directed Graphs with Negative Weights

## CS/CE 412/471 Algorithms: Design and Analysis (Spring 2025)

**Total Points: 30**

---

## Objective
In this challenge, you will work in groups to:

- Understand the fundamental algorithms and components for various shortest path algorithms.
- Demonstrate step-by-step working of the algorithm with examples and hand-drawn illustrations.
- Implement the algorithm and verify the correctness of your handcrafted solutions.

---

## The Problem
Ashraf Courier Service is responsible for delivering urgent messages between cities. The king has decreed that messages should reach their destination as quickly as possible, but couriers can take at most **two roads** to complete their journey.

Some cities are directly connected by a road, while others require passing through an intermediate city. The time taken to travel along each road varies, and couriers must always choose the fastest possible route.

Your task is to help the Ashraf Courier Service determine the shortest possible delivery time between a source city and all other cities while ensuring that no courier ever takes more than **two roads** in a single trip.

---

## Tasks

### Task 1 (10 points)
- For the given graph (Figure 1), dry run **Algorithm 1** (Figure 2), which finds the shortest distances with at most **two edges** from a source vertex **S** to all destination vertices through intermediate vertices.
- Submit **only the final graph** obtained after executing the algorithm (Figure 3).
- Ensure that the vertex positioning remains unchanged—only modify weights or add new edges.

### Task 2 (10 points)
- Implement **Algorithm 1** and visualize the resulting graph using any graph visualization library.
- Include this image as **Figure 4**.
- In the caption, mention what the output graph will illustrate if Algorithm 1 is run one more time.

### Task 3 (10 points)
- Run **Algorithm 1** for **p-1** times, where **p** is the total number of vertices in the graph (**p = 10**).
- Visualize the resulting graph using a graph visualization library.
- Include this image as **Figure 5**.
- In the caption, explain what **Algorithm 2** finds.

---

## Figures

- **Figure 1**: Sample input graph.
- **Figure 2**: Algorithm 1, which finds at-most **2-edge** distances.
- **Figure 3**: Modified graph showing **at-most 2-edge shortest distances** (Task 1). 
- **Figure 4**: Code-generated graph from **Task 2**.
- **Figure 5**: Code-generated graph from **Task 3**.

---

## Submission Guidelines
- Submit **one PDF file** including your solutions.
- Submit **one source file** containing your code.
- Clearly write your **group number, member names, and IDs** in your submission.

---

## Notes
- You may use **any programming language** of your choice for the implementation.
- Ensure that figures are clearly labeled and included in the correct order.
