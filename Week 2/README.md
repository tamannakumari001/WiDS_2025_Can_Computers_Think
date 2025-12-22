# Week 2 — Markov Decision Processes

This week you will move from bandits to full reinforcement learning environments by working directly with Markov decision processes (MDPs). The aim is to understand how to specify states, actions, transitions, and rewards—and to practise evaluating simple policies.

## Objectives

- Translate problem statements into explicit MDP formulations.
- Implement transition and reward dynamics for small environments.
- Run policy evaluation/value iteration style updates in code.
- Connect the mathematics in Sutton & Barto/Grokking RL to practical notebooks.

## Prerequisites

- Week 1 experiments completed (you are comfortable running and editing notebooks).
- Chapter 3 of Sutton & Barto skimmed for terminology (states, actions, returns).
- Optional: Chapter 2 of *Grokking Deep Reinforcement Learning* for worked MDP examples.

## Suggested workflow

1. **Recap the theory**  
   Review your notes from Sutton & Barto Chapter 3 and skim the `Markov_chains.pdf` in this folder to refresh basic probability concepts (state transitions, steady-state distributions).

2. **Open the assignment notebook**  
   Launch `Assignment_2.ipynb`. Make a personal copy (e.g. `Assignment_2_yourname.ipynb`) so you can track your edits.

3. **Model simple environments**  
   - Complete the hard-coded MDP examples (e.g. Bandit Walk) by filling in state transition dictionaries.  
   - Verify shapes and probabilities—each state’s outgoing probabilities must sum to 1.

4. **Handle larger state spaces**  
   - Follow the notebook instructions to implement transition functions programmatically when enumeration becomes cumbersome.  
   - Test your functions with a few hand-picked states to ensure they behave as expected.

5. **Evaluate policies**  
   - Use the provided utilities (or write your own loops) to compute value estimates for the policies defined in the notebook.  
   - Record observations about convergence speed and how rewards propagate through the state space.


## Deliverables

- Your completed notebook (or exported PDF) showing the MDP implementations and analysis.


## Extensions

- Implement policy iteration for one of the environments and compare with value iteration.
- Add visualisations (state diagrams, reward heatmaps) that help explain your MDP to teammates.
- Try modelling a real-world routine (e.g. daily schedule decisions) as an MDP and discuss limitations.

## Looking ahead

Week 3 bundles two classic dynamic programming challenges—Jack’s Car Rental and the Gambler’s Problem—that build directly on the skills from this notebook. Once you feel comfortable specifying and analysing MDPs, you will be ready to tackle them.

