# Understanding Reinforcement Learning

## Course Modules:

> 1. [Part I: Theory and Math](https://colab.research.google.com/github/danplotkin/mastering_rl/blob/main/mastering_rl_part1.ipynb)

>>[Introduction to RL](#scrollTo=9-9rUEY2mo9a)

>>[Reinforcement Learning vs Supervised and Unsupervised Learning](#scrollTo=akvqtK_vbUJF)

>>[Use Cases for Reinforcement Learning](#scrollTo=BWxTKKSebhwu)

>>[Markov Decision Processes (MDP)](#scrollTo=fcuasjvunYGv)

>>>[A. Markov Property](#scrollTo=DLv66adWna4G)

>>[B. Agent-Environment Interaction in MDPs](#scrollTo=JgcljOBwndhn)

>>>[C. State-Action Representation in MDPs.](#scrollTo=L0nxi9sfngNu)

>>>[D. Mars Rover Example Introduction](#scrollTo=HkgIA0ItdJaM)

>>>[E. MDP Trajectory](#scrollTo=JaxB5Uxwnif2)

>>>[F. Transition Probabilities](#scrollTo=TUtM3bW1nmjJ)

>>>>[I. Transition Probabilities with Stochastic Environment (Mars Rover)](#scrollTo=9wglnomfvLlP)

>>>[G. Expected Return](#scrollTo=MiU34uW1nrLR)

>>>>[I. Example with Mars Rover](#scrollTo=lG-R0F4l3KTE)

>>>>>[Calculating Expected Return:](#scrollTo=lG-R0F4l3KTE)

>>>>>[Calculation:](#scrollTo=lG-R0F4l3KTE)

>>>>>[Interpretation:](#scrollTo=lG-R0F4l3KTE)

>>>[H. Policies](#scrollTo=x1jrBqhWQN0s)

>>>[I. Value Functions](#scrollTo=tlamPbi7Vrvj)

>>>[J. Representing MDP as a Tuple](#scrollTo=K2g6_pReay6x)

>>[Policy Optimality](#scrollTo=jG0-HB76hwPT)

>>>[A. Policy Improvement Theorem](#scrollTo=_xrjl-zmpCwg)

>>>[B. Optimal State-Value Function](#scrollTo=_F9mu0-W4p7o)

>>>[C. Optimal Action-Value Function](#scrollTo=CR2qnP-SBYd8)

>>>[D. Bellman Optimality Equation for $Q^*$](#scrollTo=yi3HoW-Jn5HL)

>>>[E. Deriving Optimal Policy](#scrollTo=747OG0dPU7d4)

>>[Q-Learning](#scrollTo=wepK9xsw3sZS)

>>>[A. Q-Value Table](#scrollTo=3Ca3sxI3gHNv)

>>>>[I. Initialization](#scrollTo=0tDTbVXsgLKK)

>>>[B. Exploration Vs Exploitation](#scrollTo=EySyN_4OUgOR)

>>>>[I. Epsilon Greedy Strategy](#scrollTo=4SgZyIjhZPpg)

>>>[C. Q-value Update with Q-Learning Algorithm](#scrollTo=RSwVXzkCgcCW)

>>>[D. Mars Rover Q-Learning Example](#scrollTo=Dh2CauP9Z0KW)

>>>>[Step 1. Q-Value Table Initialization](#scrollTo=Dh2CauP9Z0KW)

>>>>[Step 2: Current State $s_4$](#scrollTo=Dh2CauP9Z0KW)

>>>>[Step 3: Transition and Reward](#scrollTo=Dh2CauP9Z0KW)

>>>>[Step 4: Q-Value Update](#scrollTo=Dh2CauP9Z0KW)

>>>>[Step 5: Update Q Table:](#scrollTo=Dh2CauP9Z0KW)

>>[Deep Q-Learning](#scrollTo=c3iKjQMQnG49)

>>>[A. Deep Q-Networks (DQN)](#scrollTo=KilZ4mPTzPSl)

>>>>[I. Policy Network Architecture](#scrollTo=HaEfX4bvps8r)

>>>>[II. Loss Calculation](#scrollTo=13Fgz5ZypFV9)

>>>>[III. Update Parameters](#scrollTo=z77xcioF1zvf)

>>>[B. Experience Replay & Replay Memory](#scrollTo=TsE6pvapqUEA)

>>>>[I. Replay Memory as a Tuple](#scrollTo=DBEdMyjqu-d7)

>>>>[II. Randomly Sampling Replay Memory](#scrollTo=_I2dEDDQvRKT)

>>>>[III. Training with Replay](#scrollTo=llc3SZcZvMMR)

>>[Training a DQN](#scrollTo=I7kN5qId108M)

>>>[A. Training Steps](#scrollTo=AQOc87ehbvoY)

>>>>[I. Sample a Random Batch from Replay Memory.](#scrollTo=rBmV4iBGjN1g)

>>>>[II. Preprocess the State](#scrollTo=RtuMBKEEjP6y)

>>>>[III. Forward Propagation](#scrollTo=U6o2_-EdkNjF)

>>>>[IV. Calculate Loss](#scrollTo=Dsz5GRVPjh8W)

>>>>[V. Backpropagation & Gradient Descent](#scrollTo=CSDluyVEvKXn)

>>>[B. Full Training Loop](#scrollTo=SVRu7rydwThH)

>>>[C. Limitations of Standard DQNs](#scrollTo=OPbovuUNgudF)

>>[Target Network](#scrollTo=-5wpSYDdggXg)

>>>[A. Initialization](#scrollTo=UQpvGiNMoW3c)

>>>[B. Soft Update](#scrollTo=hMazPWK0pLLm)

>>>[C. Updated Training Process](#scrollTo=yE4em57vpuIR)

>>[Next Steps](#scrollTo=nm5hJe3oo-DL)



> 2. [Part II: Implementing Reiforcement Learning in Python](https://colab.research.google.com/github/danplotkin/mastering_rl/blob/main/mastering_rl_part2.ipynb)

## About
Welcome to my course *Understanding Reinforcement Learning*! This course will be split up into two parts:
* Part I: Theory and Math
* Part II: Implementing Reiforcement Learning in Python 

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
