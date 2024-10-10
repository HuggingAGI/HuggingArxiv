# 在多模态大型语言模型中，连接器的选择是保留还是压缩？本研究将深入探讨这一问题。

发布时间：2024年10月09日

`LLM应用` `人工智能` `计算机视觉`

> To Preserve or To Compress: An In-Depth Study of Connector Selection in Multimodal Large Language Models

# 摘要

> 近年来，多模态大型语言模型（MLLM）备受瞩目。然而，关于如何构建 MLLM 架构，尤其是感知任务中连接器的选择，仍存在争议。本文深入探讨了连接器对 MLLM 性能的影响，将其分为特征保留和特征压缩两类。通过统一标准，我们将 MMBench、MME 和 SEED-Bench 的子任务分为粗粒度感知、细粒度感知和推理三类，并评估其表现。研究发现，特征保留型连接器在细粒度感知任务中表现优异，因其能保留细节视觉信息；而特征压缩型连接器虽在细粒度任务中稍逊，但在粗粒度和推理任务中速度优势明显且表现不俗。这些发现对 MLLM 架构设计与优化具有重要指导意义。

> In recent years, multimodal large language models (MLLMs) have garnered significant attention from both industry and academia. However, there is still considerable debate on constructing MLLM architectures, particularly regarding the selection of appropriate connectors for perception tasks of varying granularities. This paper systematically investigates the impact of connectors on MLLM performance. Specifically, we classify connectors into feature-preserving and feature-compressing types. Utilizing a unified classification standard, we categorize sub-tasks from three comprehensive benchmarks, MMBench, MME, and SEED-Bench, into three task types: coarse-grained perception, fine-grained perception, and reasoning, and evaluate the performance. Our findings reveal that feature-preserving connectors excel in \emph{fine-grained perception} tasks due to their ability to retain detailed visual information. In contrast, feature-compressing connectors, while less effective in fine-grained perception tasks, offer significant speed advantages and perform comparably in \emph{coarse-grained perception} and \emph{reasoning} tasks. These insights are crucial for guiding MLLM architecture design and advancing the optimization of MLLM architectures.

[Arxiv](https://arxiv.org/abs/2410.06765)