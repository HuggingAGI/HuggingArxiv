# AmpAgent：基于 LLM 的多代理系统，专为从文献中进行多阶段放大器原理图设计，实现工艺与性能的移植。

发布时间：2024年09月23日

`Agent` `电子工程` `半导体`

> AmpAgent: An LLM-based Multi-Agent System for Multi-stage Amplifier Schematic Design from Literature for Process and Performance Porting

# 摘要

> 多级放大器在模拟电路中应用广泛，但其大量组件和复杂特性需要大量人力确保稳定性。为此，我们推出了AmpAgent：一个基于LLM的多代理系统，旨在高效设计复杂放大器并进行工艺和性能优化。AmpAgent包含三个代理，分别负责文献信息提取、数学推理和器件尺寸调整，通过迭代解决设计问题。在七种多级放大器的设计中，AmpAgent显著提升了设计效率和电路性能，减少了迭代次数和执行时间，并提高了成功率。这表明LLM在复杂模拟电路设计中具有巨大潜力。

> Multi-stage amplifiers are widely applied in analog circuits. However, their large number of components, complex transfer functions, and intricate pole-zero distributions necessitate extensive manpower for derivation and param sizing to ensure their stability. In order to achieve efficient derivation of the transfer function and simplify the difficulty of circuit design, we propose AmpAgent: a multi-agent system based on large language models (LLMs) for efficiently designing such complex amplifiers from literature with process and performance porting. AmpAgent is composed of three agents: Literature Analysis Agent, Mathematics Reasoning Agent and Device Sizing Agent. They are separately responsible for retrieving key information (e.g. formulas and transfer functions) from the literature, decompose the whole circuit's design problem by deriving the key formulas, and address the decomposed problem iteratively.
  AmpAgent was employed in the schematic design of seven types of multi-stage amplifiers with different compensation techniques. In terms of design efficiency, AmpAgent has reduced the number of iterations by 1.32$ \sim $4${\times}$ and execution time by 1.19$ \sim $2.99${\times}$ compared to conventional optimization algorithms, with a success rate increased by 1.03$ \sim $6.79${\times}$. In terms of circuit performance, it has improved by 1.63$ \sim $27.25${\times}$ compared to the original literature. The findings suggest that LLMs could play a crucial role in the field of complex analog circuit schematic design, as well as process and performance porting.

[Arxiv](https://arxiv.org/abs/2409.14739)