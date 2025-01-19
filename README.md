# Aalto University Reinforcement Learning Project: Sanding Robot Optimization

## Overview

This repository contains the project work for the Reinforcement Learning course at Aalto University. The objective of this project is to optimize a robot's behavior using reinforcement learning to maximize performance in a sanding task. The robot aims to sand specified areas while avoiding painted areas, using either the **DDPG** or **PPO** algorithm, with performance improvements achieved through extensions.  

## Project Structure

### Task Descriptions

1. **Task 1: Implementing DDPG for the Sanding Robot Task**  
   The first task involves using the Deep Deterministic Policy Gradient (DDPG) algorithm to solve the sanding task.  
   - The robot operates on a 2D plane with defined sanding and no-sanding areas.
   - The action space consists of target coordinates for the robot.
   - The reward function incentivizes sanding designated areas and penalizes sanding painted areas.  

2. **Task 2: Performance Extension via Self-Imitation Learning**  
   In the second task, the base DDPG implementation is extended using **Self-Imitation Learning (SIL)** to improve the robot's performance.  
   - SIL leverages past successful experiences to enhance exploration and learning efficiency.
   - Reference: [Oh et al., 2018](https://arxiv.org/abs/1806.05635).

### Key Features
- Implementation of **DDPG** for continuous control tasks.
- Extension of DDPG with **Self-Imitation Learning** to boost performance.
- Sanding simulator with defined state, action, and reward structures.

---

## Learning Objectives
- Apply reinforcement learning algorithms (DDPG and PPO) to a new problem setting.
- Extend and modify algorithms for improved performance in challenging tasks.
- Gain practical experience with reinforcement learning concepts like reward shaping, exploration, and policy optimization.

---

## Project Components

### 1. Sanding Task
The sanding task is modeled as a Markov Decision Process (MDP):  
- **State Representation**: Robot location, sanding areas, and no-sanding areas.  
- **Action Space**: Continuous 2D target coordinates.  
- **Reward**: 
  - +1 for sanding a valid area.  
  - -1 for touching a painted area.  

### 2. Implemented Algorithms
- **DDPG**  
- **Self-Imitation Learning (SIL)**  

---
