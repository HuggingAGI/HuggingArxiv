# 一个大型循环动作模型：xLSTM 能够为机器人任务实现快速推理。

发布时间：2024年10月29日

`Agent` `机器人技术`

> A Large Recurrent Action Model: xLSTM enables Fast Inference for Robotics Tasks

# 摘要

> 摘要：近年来，强化学习（RL）领域出现了一种趋势，即通过序列建模在大规模数据集上离线训练大型动作模型。现有的模型主要基于 Transformer 架构，从而产生了强大的智能体。然而，由于推理时间慢，基于 Transformer 的方法对于实时应用（如机器人技术）不切实际。最近，提出了诸如 xLSTM 和 Mamba 等现代循环架构，它们在训练期间表现出与 Transformer 架构类似的并行化优势，同时提供快速推理。在这项工作中，我们研究了这些现代循环架构在大型动作模型中的能力。因此，我们提出了一个以 xLSTM 为核心的大型循环动作模型（LRAM），它具有线性时间推理复杂度和自然序列长度外推能力。在来自 6 个领域的 432 个任务上的实验表明，LRAM 在性能和速度方面与 Transformer 相比具有优势。

> 
Abstract:In recent years, there has been a trend in the field of Reinforcement Learning (RL) towards large action models trained offline on large-scale datasets via sequence modeling. Existing models are primarily based on the Transformer architecture, which result in powerful agents. However, due to slow inference times, Transformer-based approaches are impractical for real-time applications, such as robotics. Recently, modern recurrent architectures, such as xLSTM and Mamba, have been proposed that exhibit parallelization benefits during training similar to the Transformer architecture while offering fast inference. In this work, we study the aptitude of these modern recurrent architectures for large action models. Consequently, we propose a Large Recurrent Action Model (LRAM) with an xLSTM at its core that comes with linear-time inference complexity and natural sequence length extrapolation abilities. Experiments on 432 tasks from 6 domains show that LRAM compares favorably to Transformers in terms of performance and speed.
    

[Arxiv](https://arxiv.org/pdf/2410.22391)