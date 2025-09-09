---
title: Home
layout: minimal
---
<!-- website address
https://clearlab-sustech.github.io/ACR2024/
-->
# SDM5008 (F24) Advanced Control for Robotics

## Course Objectives

- Develop a solid foundation in robot modeling, control and learning to conduct cutting edge research in robotics
 - **Math**: Probability, optimization, stochastic systems
 - **Modeling**: Advanced rigid body kinematics and dynamics
 - **Control**: Differential IK, Model predictive control
 - **Learning**: MDP, Deep Reinforcement learning

----

## Course Information

- **Course ID**: SDM5008
- **Course Name**: Advanced Control for Robotics
- **Credit**: 3.0
- **Credit Hours**: 48.0
- **Classroom**: Classroom 524, Teaching Building One
- **Time**: Week 1-16, Wednesday 19:00 pm - 22:00 pm;
- **Teacher**: Wei Zhang(zhangw3@sustech.edu.cn)
- **TA**: Jiaqi Song(12433008@mail.sustech.edu.cn), Haokai Su(12433009@mail.sustech.edu.cn)

----

## Target Students  

- PhD students in robotics with a strong need of advanced control
- Master students in control and robotics with a strong desire to pursue PhD degree
- Students who can devote **substantial time** to read and learn outside classroom

----

## Tentative Outline

1. **Advanced Kinematics and Dynamics**
   1. Rigid body configuration and velocity
   2. Exponential coordinate of rigid body motion
   3. Kinematics of open chain
   4. Velocity Kinematics

2. **Basic Robot Control**
   1. Basics of optimization
   2. Differential IK
   3. Introductory optimal control
   4. Model Predictive Control

3. **Reinforcement learning**
   1. Probability review
   2. Markov Decision Process
   3. Basics of Neural Networks
   4. Value estimation via sampling
   5. Introduction to Policy gradient
   6. Policy gradient with baseline
   7. Advanced policy gradient

4. **Advanced topics (if time permits)**
   1. **Transformer**
   2. **robot dynamics**

## Prerequisite

- Undergraduate introductory robotics course
  - Solid background in rigid body kinematics and dynamics in the level described in standard beginner textbooks, such as:
    - “Introduction to Robotics: Mechanics and Control”, J. Craig
    - “Robot Modeling and Control”, M. Spong, S. Hutchinton, and M. Vidyasagar
- Undergraduate class in control
- Maturity in math, solid understanding in linear algebra (see tutorial notes in linear algebra), good at abstract reasoning
- Programming skills: **Python**

## Lecture Notes

- **Lecture Note 1: Rigid body configuration** [[PDF]](./LectureNotes/LN1_RigidBodyMotion.pdf) [[Notes]](./LectureNotes/Notes/LN1_RigidBodyMotion.pdf)\
  <span style="color: green;">Rigid Body Configuration, Rigid Body Velocity(Twist), Geometric Aspect of Twist: Screw Motion</span>
- **Lecture Note 2: Operator view of rigid body operation** [[PDF]](./LectureNotes/LN2_RigidBodyOperation.pdf) [[Notes]](./LectureNotes/Notes/LN2_RigidBodyOperation.pdf)\
   <span style="color: green;"> Matrix exponential, rotation operator, rigid body operator, rigid body operator for screw axis </span>
- **Lecture Note 3: Exponential coordinate of rigid rody configuration** [[PDF]](./LectureNotes/LN3_ExpCoordinate.pdf) [[Notes]](LectureNotes/Notes/LN3_ExpCoordinate.pdf)\
   <span style="color: green;"> Exponential coordinate of SO(3), Euler Angles and Euler-Like Parameterizations, Exponential coordinate of SE(3) </span>
- **Lecture Note 4: Instantaneous Velocity of Moving Frames** [[PDF]](./LectureNotes/LN4_InstantaneousVelocityofMovingFrames.pdf) [[Notes]](./LectureNotes/Notes/LN4_InstantaneousVelocityofMovingFrames.pdf)\
   <span style="color: green;"> Instantaneous Velocity of Rotating Frames, Instantaneous Velocity of Moving Frames </span>
- **Lecture Note 5: Product of Exponential and Kinematics of Open Chain** [[PDF]](./LectureNotes/LN5_kinematics.pdf) [[Notes]](./LectureNotes/Notes/LN5_kinematics.pdf)\
   <span style="color: green;"> Motivating Example, Product of Exponential Formula Derivations, Practice Example </span>
- **Lecture Note 6: Velocity Kinematics: Geometric and Analytic Jacobian of Open Chain** [[PDF]](./LectureNotes/LN6_VelocityKinematics.pdf) [[Notes]](./LectureNotes/Notes/LN6_VelocityKinematics.pdf)\
   <span style="color: green;"> Geometric Jacobian Derivations, Analyic Jacobian </span>
- **Lecture Note 7: Rigid Body Dynamics** [[PDF]](./LectureNotes/LN7_RigidBodyDynamics.pdf) [[Notes]](LectureNotes/Notes/LN7_RigidBodyDynamics.pdf)\
   <span style="color: green;"> Spatial Acceleration, Spatial Force, Spatial Momentum </span>
- **Lecture Note 8: Mujoco Tutorial** [[PDF]](./LectureNotes/LN8-MujocoTutorial.pdf) [[Notes]](LectureNotes/Notes/LN8-MujocoTutorial.pdf) \
   <span style="color: green;"> Short introduction to simulation, Introduction to Mujoco, Python Example </span>
- **Lecture Note 9: Probability Review for Reinforcement Learning** [[PDF]](./LectureNotes/LN9_F24_ProbabilityReview.pdf) [[Notes]](./LectureNotes/Notes/LN9_F24_ProbabilityReview.pdf) \
   <span style="color: green;"> Probability and Conditional Probability, Random Variables and Random Vectors, Jointly Distributed Random Vectors and Conditional Expectation </span>
- **Lecture Note 10: Markov Decision Process for Reinforcement Learning** [[PDF]](./LectureNotes/Lec10_MDP.pdf) \
    <span style="color: green;"> Markov chain, Markov decision process, Bellman equations, Simulations </span>

## Homework

- [Homework 1](./homework/hw1_F24.pdf) (due Sep 25)
- [Homework 2](./homework/hw2_F24.pdf) (due Oct 13)
- [Homework 3](./homework/hw3_F24.pdf) (due Nov 3)
- [Homework 4](./homework/hw4_F24.pdf) (due Nov 17)
- [Mini Project](./homework/miniProject.pdf) (due Oct 13)
- [Final Project](./homework/finalproject.pdf) (due Jan 8, 2025)

## MISC

- [Python Tutorial - Basics](./misc/ACR24_PythonTutorial.ipynb) (numerous Python resources are available online, you are expected to learn more by yourself)
- [Basics of Neural Network](./misc/LN0_IntroToNeuralNetwork.pdf)(Introduction to Neural Network)
- [Neural Network Coding Tutorial](./misc/Introduction_to_neural_network.ipynb) (contains the implementation of key components of a neural network, including activation functions and the MLP architecture.)
- [Mujoco Installation Tutorial](./misc/mujoco_tutorial.pdf)(contains how to install miniconda3 and mujoco.)

## Background Reading

- “Linear Algebra Review and Reference”, Zico Kolter
- “The Matrix Cook Book” - Kaare Brandt Petersen, Michael Syskind Pedersen
- [Linear algebra](https://www.bilibili.com/video/BV1eA411F7RX/)
- [Matrix exponential](https://www.bilibili.com/video/BV1Ab411d7vi/)

## Reference

- [“Mathematical introduction to robotic manipulation”, R. Murray, Z. Li, S. Sastry](./misc/MathRobotics94.pdf)
- ["Modern Robotics: Mechanics, Planning, and Control", Kevin M. Lynch and Frank C. Park, Cambridge University Press, 2017, ISBN 9781107156302](./misc/ModernRobotics.pdf)
- [“Rigid Body Dynamics Algorithms”, Roy Featherston](https://www.springer.com/gp/book/9780387743141)
- “Predictive Control for Linear and Hybrid Systems”, F. Borrelli, A. Bemporad, M. Morari, Cambridge University Press , July, 2017
- http://www.mpc.berkeley.edu/mpc-course-material 
- https://spinningup.openai.com/en/latest/
- https://rail.eecs.berkeley.edu/deeprlcourse/
- Lecture notes, and papers distributed in class
