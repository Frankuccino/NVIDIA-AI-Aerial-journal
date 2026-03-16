# Experiments

This directory documents practical experiments conducted while exploring the **NVIDIA AI Aerial ecosystem** and related technologies.

The goal is to move beyond theory and understand how the platform works through **hands-on deployment, testing, and observation**.

Experiments may involve:

- Deploying AI Aerial containers from NGC
- Running CUDA-Accelerated RAN workloads
- Testing Sionna simulations
- Exploring Omniverse Digital Twin environments
- Running GPU workloads on AWS instances

---

## Experiment Format

Each experiment should follow a consistent structure.

### Example

```
Experiment: Deploy CUDA-Accelerated RAN Container

Date:
YYYY-MM-DD

Objective
Understand how the container is deployed and what components are required.

Environment
- Cloud / Local
- GPU type
- OS
- CUDA version

Steps
1. Pull container from NGC
2. Configure environment variables
3. Run container
4. Observe logs and performance

Observations
Key things noticed during deployment or execution.

Results
Did the experiment succeed? What worked and what failed?

Lessons Learned
Important insights gained from the experiment.
```

---

## Purpose

These experiments serve to:

- validate understanding of the AI Aerial ecosystem
- document deployment procedures
- record technical challenges
- build practical experience with GPU-accelerated telecom systems

## File Structure Example

```
experiments/
experiment-01-ngc-container.md
experiment-02-sionna-simulation.md
experiment-03-aws-gpu-instance.md
```
