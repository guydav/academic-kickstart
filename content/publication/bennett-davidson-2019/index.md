---
title: "Momentum and mood in policy-gradient reinforcement learning"
date: 2019-01-01
publishDate: 2020-04-02T18:59:39.938289Z
authors: ["Daniel Bennett", "Guy Davidson", "Yael Niv"]
publication_types: ["1"]
abstract: "Policy-gradient reinforcement learning (RL) algorithms have recently been successfully applied in a number of domains. In spite of this success, however, relatively little work has explored the implications of policy-gradient RL as a model of  human learning and decision making. In this project, we derive two new policy-gradient algorithms that have implications as models of human behaviour: TD(λ) Actor-Critic with Momentum, and TD(λ) Actor-Critic with Mood. For the first algorithm, we review the concept of momentum in stochastic optimization theory, and show that it can be readily implemented in a policy-gradient RL setting. This is useful because momentum can accelerate policy gradient RL by filtering out high-frequency noise in parameter updates, and possibly also by conferring robustness against convergence to local maxima in the algorithm’s objective function. For the second algorithm, we show that a policy-gradient RL agent can implement an approximation to momentum in part by maintaining a representation of its own mood. As a proof of concept, we show that both of these new algorithms outperform a simpler algorithm that has neither momentum nor mood in a standard RL testbed, the 10-armed bandit problem. We discuss the implications of the mood algorithm as a model of the feedback between mood and learning in human decision making."
featured: false
publication: "*The 4th Multidisciplinary Conference on Reinforcement Learning and Decision Making*"
url_pdf: "http://rldm.org/papers/extendedabstracts.pdf"
---

