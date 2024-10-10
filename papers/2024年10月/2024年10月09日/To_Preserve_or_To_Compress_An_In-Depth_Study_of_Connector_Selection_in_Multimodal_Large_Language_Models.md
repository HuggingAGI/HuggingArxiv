# 在多模态大型语言模型中，连接器的选择是保留还是压缩？这是一项深入探讨的研究。

发布时间：2024年10月09日

`LLM应用` `人工智能` `计算机视觉`

> To Preserve or To Compress: An In-Depth Study of Connector Selection in Multimodal Large Language Models

# 摘要

> 近年来，多模态大型语言模型（MLLM）备受业界和学术界瞩目。然而，关于如何构建 MLLM 架构，尤其是选择适合不同感知任务的连接器，仍存在诸多争议。本文深入探讨了连接器对 MLLM 性能的影响，将连接器分为特征保留型和特征压缩型，并根据 MMBench、MME 和 SEED-Bench 三大基准，将任务细分为粗粒度感知、细粒度感知和推理三类，进行性能评估。研究发现，特征保留型连接器在细粒度感知任务中表现优异，因其能保留详尽视觉信息；而特征压缩型连接器虽在细粒度感知中稍逊一筹，但在粗粒度感知和推理任务中速度优势明显，表现亦不俗。这些发现对 MLLM 架构设计及优化具有重要指导意义。

> In recent years, multimodal large language models (MLLMs) have garnered significant attention from both industry and academia. However, there is still considerable debate on constructing MLLM architectures, particularly regarding the selection of appropriate connectors for perception tasks of varying granularities. This paper systematically investigates the impact of connectors on MLLM performance. Specifically, we classify connectors into feature-preserving and feature-compressing types. Utilizing a unified classification standard, we categorize sub-tasks from three comprehensive benchmarks, MMBench, MME, and SEED-Bench, into three task types: coarse-grained perception, fine-grained perception, and reasoning, and evaluate the performance. Our findings reveal that feature-preserving connectors excel in \emph{fine-grained perception} tasks due to their ability to retain detailed visual information. In contrast, feature-compressing connectors, while less effective in fine-grained perception tasks, offer significant speed advantages and perform comparably in \emph{coarse-grained perception} and \emph{reasoning} tasks. These insights are crucial for guiding MLLM architecture design and advancing the optimization of MLLM architectures.

[Arxiv](https://arxiv.org/abs/2410.06765)