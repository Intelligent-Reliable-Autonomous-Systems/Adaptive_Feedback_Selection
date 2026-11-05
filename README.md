# Adaptive Querying for Reward Learning from Human Feedback

This repository contains the implementation of Adaptive Feedback Selection (AFS), a framework for learning a reward function from multiple forms of human feedback to help an agent avoid undesirable states. 

The work was published in [Frontier in Robotics and AI (2026).]([url]([https://yashwanthi.xyz/adaptive-feedback-selection/static/papers/Adaptive_Querying_for_Reward_Learning_from_Human_Feedback.pdf)](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2025.1734564/full))

## Repository Structure

- `main_approach/` — Core adaptive feedback selection algorithm, feedback processing, and reward prediction.
- `baseline/` — Baseline feedback-selection method.
- `environments/` — Environment definition files and simulation utilities.
- `run_afs.py` — Entry point for AFS simulation experiments
- `run_baseline.py` — Entry point for baseline experiment

## Running the code

Clone the repo 
```
git clone https://github.com/Intelligent-Reliable-Autonomous-Systems/Adaptive_Feedback_Selection.git
cd Adaptive_Feedback_Selection
```

Run experiments from the entry points as
```
# Box-pushing experiment
python run_afs.py bp

# Vase experiment
python run_afs.py ua-vase

# Outdoor navigation experiment
python run_afs.py outdoor

# Example baseline experiment
python run_baseline.py bp 15
```
