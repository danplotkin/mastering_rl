# Mastering Reinforcement Learning: Theory, Math, and Python

## Course Modules:

> 1. [Part I: Theory and Math](https://colab.research.google.com/github/danplotkin/mastering_rl/blob/main/mastering_rl_part1.ipynb)
<details>
   <summary> Show more </summary>
   
Introduction to Reinforcement Learning

&nbsp;&nbsp;&nbsp;&nbsp;Reinforcement Learning vs Supervised and Unsupervised Learning

&nbsp;&nbsp;&nbsp;&nbsp;Use Cases for Reinforcement Learning

Markov Decision Processes (MDP)

&nbsp;&nbsp;&nbsp;&nbsp;A. Markov Property

&nbsp;&nbsp;&nbsp;&nbsp;B. Agent-Environment Interaction in MDPs

&nbsp;&nbsp;&nbsp;&nbsp;C. State-Action Representation in MDPs.

&nbsp;&nbsp;&nbsp;&nbsp;D. Mars Rover Example Introduction

&nbsp;&nbsp;&nbsp;&nbsp;E. MDP Trajectory

&nbsp;&nbsp;&nbsp;&nbsp;F. Transition Probabilities

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I. Transition Probabilities with Stochastic Environment (Mars Rover)

&nbsp;&nbsp;&nbsp;&nbsp;G. Expected Return

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I. Example with Mars Rover

&nbsp;&nbsp;&nbsp;&nbsp;H. Policies

&nbsp;&nbsp;&nbsp;&nbsp;I. Value Functions

&nbsp;&nbsp;&nbsp;&nbsp;J. Representing MDP as a Tuple

Policy Optimality

&nbsp;&nbsp;&nbsp;&nbsp;A. Policy Improvement Theorem

&nbsp;&nbsp;&nbsp;&nbsp;B. Optimal State-Value Function

&nbsp;&nbsp;&nbsp;&nbsp;C. Optimal Action-Value Function

&nbsp;&nbsp;&nbsp;&nbsp;D. Bellman Optimality Equation for $Q^*$

&nbsp;&nbsp;&nbsp;&nbsp;E. Deriving Optimal Policy

Q-Learning

&nbsp;&nbsp;&nbsp;&nbsp;A. Q-Value Table

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I. Initialization

&nbsp;&nbsp;&nbsp;&nbsp;B. Exploration Vs Exploitation

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I. Epsilon Greedy Strategy

&nbsp;&nbsp;&nbsp;&nbsp;C. Q-value Update with Q-Learning Algorithm

&nbsp;&nbsp;&nbsp;&nbsp;D. Mars Rover Q-Learning Example

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Step 1. Q-Value Table Initialization

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Step 2: Current State $s_4$

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Step 3: Transition and Reward

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Step 4: Q-Value Update

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Step 5: Update Q Table:

Deep Q-Learning

&nbsp;&nbsp;&nbsp;&nbsp;A. Deep Q-Networks (DQN)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I. Policy Network Architecture

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;II. Loss Calculation

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;III. Update Parameters

&nbsp;&nbsp;&nbsp;&nbsp;B. Experience Replay & Replay Memory

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I. Replay Memory as a Tuple

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;II. Randomly Sampling Replay Memory

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;III. Training with Replay

Training a DQN

&nbsp;&nbsp;&nbsp;&nbsp;A. Training Steps

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I. Sample a Random Batch from Replay Memory.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;II. Preprocess the State

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;III. Forward Propagation

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;IV. Calculate Loss

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;V. Backpropagation & Gradient Descent

&nbsp;&nbsp;&nbsp;&nbsp;B. Full Training Loop

&nbsp;&nbsp;&nbsp;&nbsp;C. Limitations of Standard DQNs

Target Network

&nbsp;&nbsp;&nbsp;&nbsp;A. Initialization

&nbsp;&nbsp;&nbsp;&nbsp;B. Soft Update

&nbsp;&nbsp;&nbsp;&nbsp;C. Updated Training Process

Next Steps
</details>

> 2. [Part II: Implementing Reinforcement Learning in Python](https://colab.research.google.com/github/danplotkin/mastering_rl/blob/main/mastering_rl_part2.ipynb)

## About
Welcome to my course *Mastering Reinforcement Learning: Theory, Math, and Python*! This course will be split up into two parts:
* Part I: Theory and Math
* Part II: Implementing Reinforcement Learning in Python 

By the end of this course, you will have a strong understanding on what reinforcement learning is, the mathematical foundation of reiforcement learning, Markov Decision Process (MDP), Q-learning, Deep-Q Learning, and how you can implement all of these skills using python in a real world project!

## Prerequisites

Before starting the Reinforcement Learning course, it's recommended to have the following skills and knowledge:

1. **Python Programming Skills:** Object-oriented programing skills in Python.

2. **Foundational Mathematics:** Understanding of basic calculus, linear algebra, and probability theory will be helpful for comprehending the algorithms and concepts.

3. **Machine Learning Basics:** Familiarity with fundamental concepts in machine learning, such as supervised and unsupervised learning, will provide a good foundation.

4. **Understanding of Algorithms and Data Structures:** Basic knowledge of algorithms and data structures will aid in comprehending the logic and implementation of RL algorithms.

5. **Familiarity with Markov Processes:** Having a basic understanding of Markov processes and probability will be beneficial for understanding Markov Decision Processes (MDPs).

6. **Neural Networks:** Basic understanding of neural networks and their functioning will be useful.
   
7. **Experience with Frameworks:** Familiarity with machine learning/deep learning frameworks like TensorFlow or PyTorch can be beneficial for implementing algorithms. We will be using PyTorch.
