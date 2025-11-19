# Biologically-Inspired Computation (F20BC/F21BC) Coursework

🎯 Project Goal: Teaching a Digital Brain to Learn

The core objective of this assessment is to implement and combine two biologically-inspired computation techniques—an Artificial Neural Network (ANN) and Particle Swarm Optimisation (PSO)—to solve a regression problem.

🛠️ Implementation Tasks (Building the Tools)

You must implement both algorithms from scratch:

1. Artificial Neural Network (ANN) - The Brain

Purpose: To act as a predictive model (a "digital brain"). It takes 8 inputs (concrete ingredients) and predicts one output (its compressive strength).

Key Requirement: Implement the feedforward architecture and the required activation functions (Logistic, ReLU, tanh).

Note: You will not use traditional methods like backpropagation for training.

2. Particle Swarm Optimisation (PSO) - The Swarm

Purpose: An optimization algorithm inspired by the collective movement of birds or fish. It searches for the best set of parameters.

Key Requirement: Implement the PSO algorithm as described in the course (using informants), which means each particle is influenced by a subset of the swarm, not just the global best.

🔗 The Coupling: Training the ANN with PSO

---

#This step integrates the two systems:

Particle Representation: Each particle in the PSO swarm represents a complete ANN model, encoding all its weights and biases as a single vector of values.

Training Process: The PSO adjusts these weights and biases to find the optimal configuration.

Fitness Evaluation: When a particle is evaluated, its ANN is tested against the concrete dataset. The resulting Mean Absolute Error (MAE) of the predictions becomes the particle's fitness score. PSO's job is to minimize this MAE.

🧪 Experimental Investigation (The Analysis)

The project requires an experimental study to understand how different settings (hyperparameters) affect the performance of the combined system.

Required Questions to Investigate:

ANN Architecture: How does the design (number of layers, neurons, and activation functions) influence the model's ability to solve the problem?

Resource Allocation: For a fixed computational budget (total solution evaluations), what is the optimal balance between swarm size and number of iterations?

PSO Coefficients: How does varying the acceleration coefficients (balancing social vs. cognitive components) affect the swarm's search efficiency?

📝 Deliverables and Deadline

Code (Zip File): Complete, runnable, and well-commented code for both ANN and PSO, clearly referencing the specification/pseudocode.

Report (PDF - max 6 pages): Must include sections on implementation, detailed results and discussion, and conclusions.

Group Signing Sheet: Documenting individual contributions to the paired assessment.
----
