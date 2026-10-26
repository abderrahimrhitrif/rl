# Reinforcement Learning: N-Armed Bandit Experiments

## Overview
This project explores multi-armed bandit algorithms through Jupyter notebooks, implementing stationary and non-stationary bandit simulations with epsilon-greedy exploration strategies and sample-average / constant-step-size update rules.

## Architecture & Pipeline
- **Simulation Environment**: Implements $N$-armed bandit testbed environments with stationary and non-stationary reward distributions.
- **Agent Policies**: Implements $\epsilon$-greedy exploration policies and constant step-size ($lpha$) tracking.
- **Evaluation**: Computes average rewards and percentage of optimal actions across multiple independent runs.

## Data
- **Dataset**: Synthetically generated bandit reward distributions across multi-step simulation runs.

## Method & Algorithms
- **Multi-Armed Bandits**: Reinforcement learning exploration-exploitation trade-offs using sample-average update rules and exponential recency-weighted average step sizes (`alpha`).

## Verified Results & Metrics
- Successfully simulated stationary and non-stationary $N$-armed bandit environments and visualized reward curves across various $\epsilon$ exploration parameters.

## Limitations & Caveats
- Foundational reinforcement learning simulation study.

## Run Instructions
```bash
jupyter notebook n-arms-bandit.ipynb
```

## CV Bullet Points
- Implemented stationary and non-stationary multi-armed bandit reinforcement learning simulations in Python, evaluating $\epsilon$-greedy strategies and constant step-size update rules.
- Visualized average rewards and optimal action percentages across multiple independent simulation runs.

## Claims to Avoid
- Do not claim advanced deep reinforcement learning robotics deployment.
