#  Digital Control Systems Lab — E-Puck Robot Projects

This repository contains two **mini projects** developed for the **Digital Control Systems Laboratory** course at **Amirkabir University of Technology (AUT)**.
Both projects were implemented using **Webots 2023b** and focus on **autonomous navigation**, **control design**, and **algorithmic decision-making** for an **e-puck robot**.

---

##  Overview

The goal of these projects was to design, implement, and test control and navigation algorithms that allow the e-puck robot to autonomously explore a maze environment, perform line-following tasks, and return to its starting point.
Students were encouraged to combine theoretical knowledge from digital control systems with practical implementation in simulation.

---

##  Mini Project 1 — Maze Traversal using Search Algorithms

###  Objective

Develop and demonstrate proficiency in maze traversal algorithms using a simulated robotic environment.

###  Description

The robot is required to **autonomously navigate through a maze** in Webots, mapping all reachable areas and returning to the starting point without manual intervention.
Students implemented **one of two traversal algorithms**:

* **Depth-First Search (DFS):** Explores as far as possible along each branch before backtracking.
* **Breadth-First Search (BFS):** Explores all neighboring nodes before moving deeper, ensuring the shortest path.

###  Success Criteria

* The robot successfully navigates and maps the entire maze.
* Demonstrates the traversal algorithm’s performance in real-time simulation.
* Operates autonomously with minimal error.
* Returns to the start point after completing exploration.

###  Deliverables

* Algorithm implementation code.
* Simulation setup in Webots.
* Final report describing the approach, challenges, and results.

---

##  Mini Project 2 — Maze Navigation & PID-Based Line Following

###  Objective

Design a control system that allows the e-puck robot to:

1. Navigate through a maze.
2. Identify and complete **two line-following zones**.
3. Return to the starting point after both tasks.

###  Control Design

A **PID controller** was developed and applied to elementary motion tasks such as:

* Moving straight
* Turning left / right
* Line following

The PID controller was implemented using a **discretized control formulation** to ensure stable and accurate performance in the digital environment.
**Open-loop control** was avoided for any task that could be modeled as a feedback control problem.

###  Implementation Steps

1. Write a `PID` class using a chosen discretization method.
2. Tune PID parameters for different tasks (e.g., line following, turning).
3. Integrate the PID controller into the navigation logic.
4. Combine maze traversal and line-following behaviors into a unified system.

---

##  Key Learnings

* Application of **control theory** in practical robotic systems.
* Implementation of **discrete PID control** for real-time tasks.
* Understanding **search-based path planning algorithms (DFS/BFS)**.
* Experience with **Webots simulation** and **autonomous navigation systems**.

---

## Tools & Environment

* **Webots:** 2023b
* **Robot Model:** e-puck
* **Language:** Python 
* **Control Approach:** Discrete PID control, search-based path planning

---

## 📸 Demo

*(You can add screenshots or videos of your Webots simulations here if available.)*

---

## 👨‍💻 Author

**Setayesh Khasehtarash**
Digital Control Systems Lab — Amirkabir University of Technology

Would you like me to make it slightly more **professional for a GitHub portfolio** (e.g., with badges, more polished tone, and formatted equations for PID)? That version looks great if you plan to showcase it in your MEXT or grad school applications.
