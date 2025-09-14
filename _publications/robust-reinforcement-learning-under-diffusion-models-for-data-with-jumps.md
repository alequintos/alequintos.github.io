---
title: "Robust Reinforcement Learning under Diffusion Models for Data with Jumps"
collection: publications
permalink: /publication/robust-reinforcement-learning-under-diffusion-models-for-data-with-jumps
venue: 'arXiv'
excerpt: ''
paperurl: 'https://arxiv.org/abs/2411.11697'
date: 2024-11-18
citation: 'Jiang, C., Kim D., Quintos, A., Wang, Y. Robust Reinforcement Learning under Diffusion Models for Data with Jumps. <i>Preprint</i> (2024).'

---

Reinforcement Learning (RL) has proven effective in solving complex decision-making tasks across various domains, but challenges remain in continuous-time settings, particularly when state dynamics are governed by stochastic differential equations (SDEs) with jump components. In this paper, we address this challenge by introducing the Mean-Square Bipower Variation Error (MSBVE) algorithm, which enhances robustness and convergence in scenarios involving significant stochastic noise and jumps. We first revisit the Mean-Square TD Error (MSTDE) algorithm, commonly used in continuous-time RL, and highlight its limitations in handling jumps in state dynamics. The proposed MSBVE algorithm minimizes the mean-square quadratic variation error, offering improved performance over MSTDE in environments characterized by SDEs with jumps. Simulations and formal proofs demonstrate that the MSBVE algorithm reliably estimates the value function in complex settings, surpassing MSTDE's performance when faced with jump processes. These findings underscore the importance of alternative error metrics to improve the resilience and effectiveness of RL algorithms in continuous-time frameworks.

[View paper here](https://arxiv.org/pdf/2411.11697)
