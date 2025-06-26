Fire Hawk Optimizer (FHO) Project
Overview
The Fire Hawk Optimizer (FHO) is a nature-inspired metaheuristic optimization algorithm that simulates the unique hunting and fire-spreading behaviors of fire hawks—birds observed in Australia that use fire to flush out prey. The algorithm is designed to solve complex, high-dimensional optimization problems by effectively balancing exploration (searching globally) and exploitation (refining locally).

Key Features

Nature-Inspired Intelligence: Models predator-prey interactions and fire-spreading behavior for robust optimization.

Exploration & Exploitation: Dynamically balances global search (exploration) and local refinement (exploitation) to avoid local optima.

Adaptive Mechanisms: Includes adaptive speed control, momentum-based updates, and dynamic position updates for improved convergence.

Enhanced Initialization: Uses Chebyshev chaos mapping for better population distribution and reduced risk of poor clustering.

Lévy Flight Integration: Incorporates Lévy flight for long-range jumps, enhancing global search and escape from local optima.

Phasor Operator: Implements a quantum-inspired phasor operator for controlled, periodic perturbations, ensuring smooth transition from exploration to exploitation.

Hybridization Capability: Can be combined with other algorithms (e.g., PSO, DE) for improved performance on specific problem types.

Modifications & Improvements

Chebyshev Initialization: Replaces random initialization to ensure well-distributed starting points.

Lévy Flight: Introduces heavy-tailed step sizes for better exploration.

Phasor Operator: Adds periodic, non-linear perturbations to escape local optima.

Adaptive Weighting: Dynamically assigns importance to promising regions for focused search.

Multiple Fire Hawks: Enables cooperative swarm behavior for parallel exploration and exploitation.

Performance & Advantages

Faster Convergence: Enhanced FHO demonstrates faster and more reliable convergence compared to standard FHO and other metaheuristics (PSO, GA, ACO, GWO, WOA, etc.).

Superior Solution Quality: Consistently achieves lower error rates and better final fitness values across benchmark functions.

Robustness: Maintains stable, non-oscillatory convergence even in high-dimensional and multimodal landscapes.

Scalability: Performs well on both small and large-scale optimization problems, including engineering, machine learning, and combinatorial optimization tasks.

Applications

Mathematical Optimization: Benchmark functions (Sphere, Rastrigin, Rosenbrock, etc.)

Machine Learning: Feature selection, hyperparameter tuning, neural network training

Engineering: Power system optimization, route planning, logistics, signal processing

Combinatorial Problems: Traveling Salesman, Knapsack, scheduling

Project Details

Developed by: Kanishk Sharma, Kamran Ahmed, Ajisth Shukla

Supervisor: Dr. Ankur Gupta, Netaji Subhas University of Technology, Delhi

Course: B.Tech in Computer Science and Engineering (Artificial Intelligence)

Period: January 2025 – May 2025

Source Code & Documentation
This repository contains the implementation of the Fire Hawk Optimizer (FHO) and its enhanced variants, along with comprehensive documentation, benchmarking scripts, and comparative analysis against other metaheuristic algorithms# Modified_Fire_Hawk_Optimisation
