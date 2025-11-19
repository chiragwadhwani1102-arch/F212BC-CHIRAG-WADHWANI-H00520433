# Biologically-Inspired Computation (F20BC/F21BC) Coursework

#🎯 Project Goal: Teaching a Digital Brain to Learn

<P>The core objective of this assessment is to implement and combine two biologically-inspired computation techniques—an Artificial Neural Network (ANN) and Particle Swarm Optimisation (PSO)—to solve a regression problem.</P>

#🛠️ Implementation Tasks (Building the Tools)

<P>You must implement both algorithms from scratch:

1. Artificial Neural Network (ANN) - The Brain

<P>Purpose: To act as a predictive model (a "digital brain"). It takes 8 inputs (concrete ingredients) and predicts one output (its compressive strength).<?P>

<P>Key Requirement: Implement the feedforward architecture and the required activation functions (Logistic, ReLU, tanh).</P>

<P>Note: You will not use traditional methods like backpropagation for training.</p>

2. Particle Swarm Optimisation (PSO) - The Swarm

<P>Purpose: An optimization algorithm inspired by the collective movement of birds or fish. It searches for the best set of parameters.</P>

<P>Key Requirement: Implement the PSO algorithm as described in the course (using informants), which means each particle is influenced by a subset of the swarm, not just the global best.</P>

🔗 The Coupling: Training the ANN with PSO

---

#This step integrates the two systems:

<p>Particle Representation: Each particle in the PSO swarm represents a complete ANN model, encoding all its weights and biases as a single vector of values.</p>

<p>Training Process: The PSO adjusts these weights and biases to find the optimal configuration.</p>

<p>Fitness Evaluation: When a particle is evaluated, its ANN is tested against the concrete dataset. The resulting Mean Absolute Error (MAE) of the predictions becomes the particle's fitness score. PSO's job is to minimize this MAE.</p>

#🧪 Experimental Investigation (The Analysis)

<p>The project requires an experimental study to understand how different settings (hyperparameters) affect the performance of the combined system.</p>

<p>Required Questions to Investigate:</p>

<p>ANN Architecture: How does the design (number of layers, neurons, and activation functions) influence the model's ability to solve the problem?</p>

<p>Resource Allocation: For a fixed computational budget (total solution evaluations), what is the optimal balance between swarm size and number of iterations?</p>

<p>PSO Coefficients: How does varying the acceleration coefficients (balancing social vs. cognitive components) affect the swarm's search efficiency?</p>

#📝 Deliverables and Deadline

<p>Code (Zip File): Complete, runnable, and well-commented code for both ANN and PSO, clearly referencing the specification/pseudocode.</p>

<p>Report (PDF - max 6 pages): Must include sections on implementation, detailed results and discussion, and conclusions.</p>

<P>Group Signing Sheet: Documenting individual contributions to the paired assessment.</P>
----
