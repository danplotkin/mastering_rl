# Mastering Reinforcement Learning: Theory, Math, and Python

## Notebooks

[*Part I: Theory and Math*](https://colab.research.google.com/github/danplotkin/mastering_rl/blob/main/mastering_rl_part1.ipynb)
<details>
   <summary>&nbsp;Show table of contents</summary>
&nbsp;
   
> 1 - Introduction to Reinforcement Learning
>
> 2 - Reinforcement Learning vs Supervised and Unsupervised Learning
>
> 3 - Use Cases for Reinforcement Learning
>
> 4 - Markov Decision Processes (MDP)
>
>> A. Markov Property
>>
>> B. Agent-Environment Interaction in MDPs
>>
>> C. State-Action Representation in MDPs.
>>
>> D. Mars Rover Example Introduction
>>
>> E. MDP Trajectory
>>
>> F. Transition Probabilities
>>
>>> I. Transition Probabilities with Stochastic Environment (Mars Rover)
>>>
>> G. Expected Return
>>
>>> I. Example with Mars Rover
>>>
>> H. Policies
>>
>> I. Value Functions
>>
>> J. Representing MDP as a Tuple
>>
> 5 - Policy Optimality
>
>> A. Policy Improvement Theorem
>>
>> B. Optimal State-Value Function
>>
>> C. Optimal Action-Value Function
>>
>> D. Bellman Optimality Equation for $Q^*$
>>
>> E. Deriving Optimal Policy
>>
> 6 - Q-Learning
>
>> A. Q-Value Table
>>
>>> I. Initialization
>>>
>> B. Exploration Vs Exploitation
>>
>>> I. Epsilon Greedy Strategy
>>>
>> C. Q-value Update with Q-Learning Algorithm
>>
>> D. Mars Rover Q-Learning Example
>>
> 7 - Deep Q-Learning
>
>> A. Deep Q-Networks (DQN)
>>
>>> I. Policy Network Architecture
>>>
>>> II. Loss Calculation
>>>
>>> III. Update Parameters
>>>
>> B. Experience Replay & Replay Memory
>>
>>> I. Replay Memory as a Tuple
>>>
>>> II. Randomly Sampling Replay Memory
>>>
>>> III. Training with Replay
>>>
> 8 - Training a DQN
>
>> A. Training Steps
>>
>>> I. Sample a Random Batch from Replay Memory.
>>>
>>> II. Preprocess the State
>>>
>>> III. Forward Propagation
>>>
>>> IV. Calculate Loss
>>>
>>> V. Backpropagation & Gradient Descent
>>>
>> B. Full Training Loop
>>
>> C. Limitations of Standard DQNs
>>
> 9 - Target Network
>
>> A. Initialization
>>
>> B. Soft Update
>>
>> C. Updated Training Process
>>
> 10 - Next Steps
</details>

[*Part II: Implementing Reinforcement Learning in Python*](https://colab.research.google.com/github/danplotkin/mastering_rl/blob/main/mastering_rl_part2.ipynb)

<details>
   <summary>&nbsp;Show table of contents</summary>
&nbsp;

> 1 - Gymnasium
>
> 2 - The Cartpole Envirnonment
>
> 3 - Developing a Cartpole Agent
>
>> A. Install Gymnasium
>>
>> B. Import Required Libaries
>>
>> C. Initialize Envirnonment
>>
>> D. Create Replay Memory
>>
>> E. Build Deep Q-Network
>>
>> F. Define Hyperparameters
>>
>> G. Define Policy and Target Network
>>
>> H. Create Policy Network Tracker
>>
>> I. Train Agent
>>
>>> I. Create Math Functions for Training
>>>
>>> II. Create Agent Class
>>>
>>> III. Intialize Agent
>>>
>>> IV. Train Agent
>>>
>>> V. Evaluate Agent
>>>
>> J. Solve Problem
</details>

## About
Welcome to my notebook crash course *Mastering Reinforcement Learning: Theory, Math, and Python*! This course will be split up into two parts:
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
