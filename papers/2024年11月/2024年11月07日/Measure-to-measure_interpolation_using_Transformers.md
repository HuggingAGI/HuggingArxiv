# 使用 Transformer 的度量到度量插值

发布时间：2024年11月07日

`LLM理论`

> Measure-to-measure interpolation using Transformers

# 摘要

> 变压器是深度神经网络架构，支撑着大型语言模型最近的成功。与可以被视为点对点映射的更经典架构不同，变压器作为一种度量到度量的映射，在单位球面上实现为特定的相互作用粒子系统：输入是提示中令牌的经验度量，其演变由连续性方程控制。事实上，变压器不限于经验度量，原则上可以处理任何输入度量。随着变压器处理的数据的性质迅速扩展，研究它们作为从任意度量到另一个任意度量的映射的表达能力是很重要的。为此，我们提供了一个明确的参数选择，允许单个变压器将 N 个任意输入度量与 N 个任意目标度量相匹配，在最小假设下，每对输入 - 目标度量都可以通过某些传输映射来匹配。

> Transformers are deep neural network architectures that underpin the recent successes of large language models. Unlike more classical architectures that can be viewed as point-to-point maps, a Transformer acts as a measure-to-measure map implemented as specific interacting particle system on the unit sphere: the input is the empirical measure of tokens in a prompt and its evolution is governed by the continuity equation. In fact, Transformers are not limited to empirical measures and can in principle process any input measure. As the nature of data processed by Transformers is expanding rapidly, it is important to investigate their expressive power as maps from an arbitrary measure to another arbitrary measure. To that end, we provide an explicit choice of parameters that allows a single Transformer to match $N$ arbitrary input measures to $N$ arbitrary target measures, under the minimal assumption that every pair of input-target measures can be matched by some transport map.

[Arxiv](https://arxiv.org/abs/2411.04551)