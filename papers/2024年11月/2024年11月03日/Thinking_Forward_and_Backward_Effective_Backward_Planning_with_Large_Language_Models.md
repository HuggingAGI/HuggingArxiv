# 《思考前与后：借助大型语言模型实现有效的向后规划》

发布时间：2024年11月03日

`LLM应用` `语言模型`

> Thinking Forward and Backward: Effective Backward Planning with Large Language Models

# 摘要

> 大型语言模型（LLMs）已展现出非凡的推理与规划能力。此领域先前的多数工作借助 LLMs 从初始状态按步骤推理至目标状态或标准，实现了有效的正向推理。不过，许多规划问题存在固有不对称性，比如目标附近有瓶颈时，从目标反向规划会容易得多。我们受此启发，证明这种偏差在 LLM 规划中同样存在：某一方向的规划性能与该方向问题的规划复杂度相关。然而，我们的实验也揭示了一些系统偏差，致使反向规划效果不佳。基于此，我们为 LLMs 提出一种反向规划算法，先翻转问题，再在翻转后的问题中正向规划。这有助于规避反向偏差，生成更多样的候选规划，并利用规划问题中正向和反向的不对称性——我们发现，在三个规划领域，将双向规划与自我验证相结合，能使整体规划成功率提升 4 - 24％。

> Large language models (LLMs) have exhibited remarkable reasoning and planning capabilities. Most prior work in this area has used LLMs to reason through steps from an initial to a goal state or criterion, thereby effectively reasoning in a forward direction. Nonetheless, many planning problems exhibit an inherent asymmetry such that planning backward from the goal is significantly easier -- for example, if there are bottlenecks close to the goal. We take inspiration from this observation and demonstrate that this bias holds for LLM planning as well: planning performance in one direction correlates with the planning complexity of the problem in that direction. However, our experiments also reveal systematic biases which lead to poor planning in the backward direction. With this knowledge, we propose a backward planning algorithm for LLMs that first flips the problem and then plans forward in the flipped problem. This helps avoid the backward bias, generate more diverse candidate plans, and exploit asymmetries between the forward and backward directions in planning problems -- we find that combining planning in both directions with self-verification improves the overall planning success rates by 4-24% in three planning domains.

[Arxiv](https://arxiv.org/abs/2411.01790)