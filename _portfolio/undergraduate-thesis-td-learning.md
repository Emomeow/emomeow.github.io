---
title: "Undergraduate Thesis: Temporal Difference Algorithm's Implicit Bias and Continuous Modeling"
excerpt: "PyTorch implementation comparing semi-gradient and true-gradient TD learning with neural function approximation, exploring implicit regularization and convergence properties in reinforcement learning."
collection: portfolio
---

## Overview

This repository implements offline reinforcement learning experiments using a fully-connected neural network (FCNN) to approximate Q-functions, investigating the implicit bias and convergence behavior of temporal difference (TD) learning algorithms.

**[View on GitHub](https://github.com/Emomeow/Undergraduate-Thesis)**

## Methods

- **Semi-gradient TD learning** with neural function approximation
- **True-gradient TD learning** with neural function approximation
- **Environment**: Deterministic 3-state MDP for controlled convergence experiments
- **Replay buffer**: Offline batch learning with stored transitions
- **Visualization**: Convergence curves, learned policies, and state-action value functions

## Key Results

Compared convergence behavior, implicit regularization effects, and learned policy quality between semi-gradient and true-gradient TD methods across multiple environment settings. Results visualized as accumulated rewards, loss curves, and value function heatmaps.

## Tools

**Python**: PyTorch, NumPy, Matplotlib, Seaborn, Gymnasium, Pygame
