# CompMechanic_Transformer

This repository contains code for training transformer models on non-ergodic processes and analyzing the learned representations through the lens of computational mechanics. The goal is to investigate whether transformer models learn to represent belief states and perform Bayesian updating, even when it is not necessary for the prediction task.

## Contents

- `D3.ipynb`: Initial exploration and experiments for the Weighted D3 Dice process.
- `D3_updated.ipynb`: Updated experiments with improvements for the Weighted D3 Dice process.
- `TrainingTransformer.ipynb`: Code for training transformer models on sequential data.
- `glue_process1.ipynb`: Data processing script for generating training data from the Weighted Coins processes.

## Processes

The following non-ergodic processes are used for training and analysis:

1. **Weighted Coins**: Three indistinguishable coins with different probabilities of emitting tokens (one fair, two biased).
2. **Weighted Coins with One Distinct Face**: Similar to Weighted Coins, but one biased side emits a distinct token.
3. **Weighted D3 Dice**: Three outcomes, each weighted towards a different token. No transitions between hidden states.
