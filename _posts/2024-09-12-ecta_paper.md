---
title: "Accepted Paper at ECTA2024"
layout: archive
tag: foutics
---

Quentin Vacher's first paper has been accepted at the [16th International Conference on Evolutionary Computation Theory and Applications (ECTA)](https://ecta.scitevents.org/).

Paper citation:
```
Vacher, Q.; Beuve, N.; Allaire, P.; Marty, T.; Dardaillon, M. and Desnos, K. (2024). Hybrid Genetic Programming and Deep Reinforcement Learning for Low-Complexity Robot Arm Trajectory Planning.  In Proceedings of the 16th International Joint Conference on Computational Intelligence, ISBN 978-989-758-721-4, ISSN 2184-3236, pages 137-148.    
```

Abstract:
Robot arm control is a technological challenge where an algorithm needs to learn a deep understanding of spatial navigation. In particular, spatial navigation requires learning the relationship between the motor joint angular positions and the Cartesian coordinates of the robot. Trajectory planning is an even more complex challenge, where the algorithm must create a trajectory between two coordinates that does not cause a collision. State-of-the-art algorithms capable of solving trajectory planning are based on deep Reinforcement Learning (RL). These algorithms achieve high accuracy but suffer from high computational complexity. This paper proposes to use a genetic RL algorithm, the Tangled Program Graphs (TPGs), to solve trajectory planning. Using a genetic process, the TPGs generate a graph of programs with low inference complexity. On a first trajectory planning problem, the algorithm used achieves performance close to the state-of-the-art, but with a 100 less execution time and a 20× smaller model size. On a second and more difficult problem, the TPGs are not able to learn with efficiency. We propose a hybrid solution that mixes the TPGs and a state-of-the-art deep RL algorithm, the Soft Actor-Critic (SAC). This solution achieves better performance than the state-of-the-art for both problems, with 6 to 20 times faster execution times.