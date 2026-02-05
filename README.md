# Dual-Path Convergence: KL Drift vs Gain Control

Real-time visualization comparing two distinct optimization strategies that both minimize variational free energy through different mechanisms.

## Overview

This simulation demonstrates how gradient descent can achieve the same objective (minimizing KL divergence) through two fundamentally different paths:

- **Purification Path**: Direct geometric correction toward the target
- **Annealing Path**: Adaptive gain scaling that decays learning sensitivity

Both regimes minimize the same variational free-energy functional but employ different optimization dynamics.

