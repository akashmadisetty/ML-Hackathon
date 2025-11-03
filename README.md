# Hackman: ML Hangman Agent

## Overview
This project tackles the Hangman-inspired challenge by building an intelligent assistant that solves word puzzles with minimal mistakes. The solution blends probabilistic modeling with reinforcement learning to make informed letter guesses.

## Challenge Summary
- **Hidden Markov Model (HMM):** Trained on the provided 50,000 word corpus to estimate per-letter probabilities conditioned on the current game state.
- **Reinforcement Learning (RL) Agent:** Uses HMM output, game state, and reward signals to choose optimal guesses within a custom Hangman environment.
- **Evaluation:** Performance measured over 2,000 games with score = `(Success Rate * 2000) - (Total Wrong Guesses * 5) - (Total Repeated Guesses * 2)`.

## Development Roadmap
- Implement HMM training pipeline and persist learned parameters.
- Build Hangman environment with configurable game rules.
- Develop RL agent (baseline tabular Q-learning followed by DQN if needed).
- Integrate training loop combining HMM predictions with RL decision-making.
- Capture evaluation metrics and visualizations for inclusion in the final report.

## Files
 - HMM_Training - Part1
 - RL_Agent_and_evals -Part2
