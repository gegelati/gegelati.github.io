---
title: "Accepted Paper at EuroGP 2026"
layout: archive
tag: foutics
---

Quentin Vacher paper on multi-tasking has been accepted at the [European Conference on Genetic Programming (EuroGP)](https://www.evostar.org/2026/eurogp/).

Paper citation:
```
Q Vacher, N Beuve, M Dardaillon, K Desnos, Multi-Action Tangled Program Graphs for Multi-Task Reinforcement Learning with Continuous Control. European Conference on Genetic Programming (EuroGP), April 2026, Apr 2026, Toulouse, France. pp.259-274.
```

Paper open access: [HAL](https://hal.science/hal-05604527)

Paper artifacts: [Gegelati repo](https://github.com/gegelati/EUROGP-2026)

Abstract:
Over the past few decades, machine learning has been widely used to learn complex tasks. Reinforcement Learning (RL), inspired by human behavior, is a great example, as it involves developing specific behaviours for specific tasks. To further challenge algorithms, Multi-Task RL (MTRL) environments have been introduced, requiring a single model to learn multiple behaviors. The Tangled Program Graph (TPG) algorithm is a Genetic Programming (GP) algorithm designed for discrete MTRL environments. Recently, the MAPLE algorithm has been proposed, as another GP algorithm that achieves high results in single task continuous RL environments. A variation of the TPG is proposed alongside MAPLE, named Multi-Action TPG (MATPG) that aggregates MAPLE agents, and creates a control flow to activate them. Initially tested on single task RL environments only, MATPG achieved similar results to MAPLE. In this work, we present a new benchmark based on the MuJoCo Half Cheetah from Gymnasium. This benchmark features five distinct obstacles that are randomly positioned in front of the agent, each of which demands a unique behavior. This benchmark serves as a use case for MATPG, to prove its ability as a GP solution for continuous MTRL environments. Our experiments demonstrate its superiority in this multi-task use case when combined with lexicase selection. Furthermore, we examine the interpretability of the evolved graph, revealing that the decision flow of the model is fully interpretable.