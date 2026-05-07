---
title: "Accepted Paper at GECCO 2025"
layout: archive
tag: foutics
---

Quentin Vacher paper on MAPLE has been accepted at the [25th Genetic and Evolutionary Computation Conference (GECCO)](https://gecco-2025.sigevo.org/HomePage).

Paper citation:
```
Q Vacher, S Kelly, A Naqvi, N Beuve, T Djavaherpour, M Dardaillon, K Desnos, MAPLE: Multi-Action Programs through Linear Evolution for Continuous Multi-Action Reinforcement Learning. 2025 Genetic and Evolutionary Computation Conference (GECCO 2025), Jul 2025, Malaga, Spain. pp.1062-1071.
```

Paper open access: [HAL](https://hal.science/hal-05196344/)

Paper artifacts: [Gegelati repo](https://github.com/gegelati/GECCO-2025)

Abstract:
Over the last decades, the need to solve complex tasks using machine learning techniques has grown significantly. Deep learning algorithms achieve state-of-the-art performance in most tasks, but at the cost of high computational complexity and limited interpretability. In domains such as Reinforcement Learning (RL), understanding the agent behavior ensures reliability and safety. In this work, we explore Genetic Programming (GP) as a promising solution for RL tasks, providing simpler and more interpretable solutions. While GP achieves competitive results in low-complexity environments, it struggles in environments with high-dimensional action spaces. To address this, we propose Multi-Action Programs through Linear Evolution (MAPLE), a GP algorithm in which the agent is a team of multiple Linear Genetic Programs (LGPs), each responsible for an action. MAPLE is evaluated on the MuJoCo suite and outperforms state-of-the-art GP algorithms and a small deep RL model. It achieves comparable performance to a larger deep RL network in low-dimensional environments while maintaining significantly lower complexity. By decomposing the action decision into different programs, it is possible to understand which parts of the states are needed for each action. This demonstrates the potential of MAPLE for interpretable and efficient solutions in RL.