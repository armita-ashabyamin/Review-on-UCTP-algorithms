# Review-on-UCTP-algorithms
A research-driven implementation of hybrid genetic algorithms (FGASA, FGARI, FGATS) for solving the University Course Timetabling Problem (UCTP), integrating fuzzy logic and metaheuristics like Simulated Annealing and Tabu Search to optimize complex academic scheduling under hard and soft constraints.

University Course Timetabling Problem (UCTP) Solver

This project presents a comprehensive approach to solving the University Course Timetabling Problem (UCTP) using advanced optimization techniques. UCTP is a well-known NP-hard problem involving the assignment of courses, instructors, rooms, and time slots while satisfying a set of hard and soft constraints.
📌 Overview

The project explores and compares several metaheuristic algorithms for solving UCTP, including:

    🐜 Ant Colony Optimization (ACO)

    🔍 Tabu Search (TS)

    ❄️ Simulated Annealing (SA)

Building on this foundation, it introduces three novel hybrid genetic algorithms:

    FGASA – Fuzzy Genetic Algorithm with Simulated Annealing

    FGARI – Fuzzy Genetic Algorithm with Random Iterative Local Search

    FGATS – Fuzzy Genetic Algorithm with Tabu Search

These algorithms incorporate fuzzy logic to handle soft constraint violations and local search enhancements to avoid local optima and improve solution quality.
🎯 Problem Definition

UCTP involves assigning:

    Courses to time slots and rooms

    Instructors to courses

    Students to non-conflicting schedules

✅ Hard Constraints:

    No overlapping courses for the same curriculum

    No double-booking of rooms or instructors

    Room capacity and equipment must match course requirements

💡 Soft Constraints:

    Instructor preferences

    Balanced daily student schedules

    Avoiding late-day classes

    Minimizing idle time between classes

🧠 Algorithmic Contributions

Each hybrid algorithm enhances a standard Genetic Algorithm (GA) by:

    Using fuzzy logic to evaluate soft constraint violations

    Integrating local search techniques (SA, TS, or random iterative search) to refine solutions

    Improving convergence and escaping local minima

📊 Results

Experimental results demonstrate that the proposed hybrid algorithms outperform traditional methods in generating high-quality, feasible timetables under real-world constraints.
