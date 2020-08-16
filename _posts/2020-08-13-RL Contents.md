---
title: "RL Contents"
date: 2020-08-13 12:46:00 -0400
categories: RL
---
# Reinforcement Learning: An Introduction - Sutton, Barto
## 1. Tabular Solution Methods
- Multi-armed Bandits
- Finite Markov Decision Processes
- Dynamic Programming
- Monte Carlo Methods
- Temporal-Difference Learining
- Multi-step Bootstrapping
- Planning and Learning with Tabular Methods

## 2. Approximate Solution Methods
- On-policy Prediction with Approximation
- On-policy Control with Approximation
- Off-policy Methods with Approximation
- Eligibility Traces
- Policy Gradient Methods

# David Silver
## Part I: Elementary Reinforcement Learning

### Lec1. Introduction to Reinforcement Learning
- About Reinforcement Learning
- The Reinforcement Learning Problem
	- Reward
	- Environments
	- State
- Inside An RL Agent
- Problems within Reinforcement Learning

### Lec2. Markov Decision Processes
- Markov Processes
	- Markov Property
	- Markov Chains
- Markov Reward Processes
	- MRP
	- Return
	- Value Function
	- Bellman Equation
- Markov Decision Processes
	- MDP
	- Policies
	- Value Functions
	- Bellman Expectation Equation
	- Optimal Value Functions
	- Bellman Optimality Equation
- Extensions to MDPs
	- Infnite MDPs
	- Partially Observable MDPs
	- Average Reward MDPs

### Lec3. Planning by Dynamic Programming
- What is Dynamic Programming?
- Policy Evaluation
	- Iterative Policy Evaluation
	- Example: Small Gridworld
- Policy Iteration
	- Example: Jack's Car Rental
	- Policy Improvement
	- Extensions to Policy Iteration
- Value Iteration
	- Value Iteration in MDPs
	- Summary of DP Algorithms
- Extensions to Dynamic Programming
	- Asynchronous Dynamic Programming
	- Full-width and sample backups
	- Approximate Dynamic Programming
- Contraction Mapping

### Lec4. Model-Free Prediction
- Monte-Carlo Learning
	- Blackjack Example
	- Incremental Monte-Carlo
- Temporal-Difference Learning
	- Driving Home Example
	- Random Walk Example
	- Batch MC and TD
	- Unifed View
- TD(λ)
	- n-Step TD
	- Forward View of TD(λ)
	- Backward View of TD(λ)
	- Relationship Between Forward and Backward TD
	- Forward and Backward Equivalence

### Lec5. Model-Free Control
- On-Policy / Off-Policy Learning
- On-Policy Monte-Carlo Control
	- Generalised Policy Iteration
	- Exploration #(epsilon-Greedy)
	- GLIE
	- Blackjack Example
- On-Policy Temporal-Difference Learning
	- Sarsa(λ)
- Off-Policy Learning
	- Importance Sampling
	- Q-Learning

- Summary
	- Relationship Between DP and TD

## Part II: Reinforcement Learning in Practice

### Lec6. Value Function Approximation
- Introduction
- Incremental Methods
	- Gradient Descent
	- Linear Function Approximation
	- Incremental Prediction Algorithms
	- Incremental Control Algorithms
	- Mountain Car
	- Convergence

- Batch Methods
	- Least Squares Prediction
	- Least Squares Control

### Lec7. Policy Gradient
- Introduction
	- Rock-Paper-Scissors Example
	- Aliased Gridworld Example
	- Policy Search (Policy Objective Functions, Policy Optimisation)
- Finite Difference Policy Gradient
	- AIBO example
- Monte-Carlo Policy Gradient
	- Likelihood Ratios
	- Policy Gradient Theorem
- Actor-Critic Policy Gradient
	- Compatible Function Approximation
	- Advantage Function Critic
	- Eligibility Traces
	- Natural Policy Gradient
	- Snake example

### Lec8. Integrating Learning and Planning
- Introduction
	- Model-Based and Model-Free RL
- Model-Based Reinforcement Learning
	- Learning a Model
	- Planning with a Model
- Integrated Architectures
	- Dyna
- Simulation-Based Search
	- Monte-Carlo Search
	- MCTS in Go
	- Temporal-Difference Search

### Lec9. Exploration and Exploitation
- Introduction
	- Exploration vs. Exploitation Dilemma
- Multi-Armed Bandits
	- Regret
	- Greedy and epsilon-greedy algorithms
	- Lower Bound
	- Upper Confidence Bound
- Contextual Bandits
	- Linear UCB
- MDPs
	- Optimistic Initialisation
	- Optimism in the Face of Uncertainty
	- Probability Matching
	- Information State Search

### Lec10. Classic Games
- State of the Art
- Game Theory
- Minimax Search
- Self-Play Reinforcement Learning
- Combining Reinforcement Learning and Minimax Search
- Reinforcement Learning in Imperfect-Information Games
- Conclusions
