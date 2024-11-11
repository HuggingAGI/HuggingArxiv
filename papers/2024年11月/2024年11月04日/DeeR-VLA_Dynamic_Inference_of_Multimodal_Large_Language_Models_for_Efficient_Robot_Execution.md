# DeeR-VLA：用于高效机器人执行的多模态大型语言模型的动态推理

发布时间：2024年11月04日

`LLM应用` `机器人` `计算机视觉`

> DeeR-VLA: Dynamic Inference of Multimodal Large Language Models for Efficient Robot Execution

# 摘要

> 多模态大型语言模型（MLLM）在处理复杂的语言和视觉数据方面展现出了卓越的理解和推理能力。这些进步激发了建立一个能够精通理解复杂人类指令并完成各种具身任务的通用机器人 MLLM 的愿景。然而，由于机器人平台通常可用的计算和内存容量有限，为现实世界中的机器人开发 MLLM 具有挑战性。相比之下，MLLM 的推理涉及存储数十亿个参数并进行大量计算，对硬件提出了很高的要求。在我们的论文中，我们为机器人视觉 - 语言 - 动作模型（DeeR-VLA，或简称为 DeeR）提出了一个动态提前退出框架，该框架根据当前的每种情况自动调整激活的 MLLM 的大小。该方法利用了 MLLM 中的多出口架构，这使得模型一旦针对特定情况激活了适当大小的模型就可以终止处理，从而避免进一步的冗余计算。此外，我们开发了新的算法，为 DeeR 建立了基于预定义需求（如平均计算成本（即功耗）以及峰值计算消耗（即延迟）和 GPU 内存使用）的提前终止标准。这些增强确保 DeeR 在不同的资源约束下高效运行，同时保持有竞争力的性能。在 CALVIN 机器人操作基准上，DeeR 在不影响性能的情况下，将 LLM 的计算成本显著降低了 5.2 - 6.5 倍，将 LLM 的 GPU 内存降低了 2 - 6 倍。代码和检查点可在 https://github.com/yueyang130/DeeR-VLA 获得。

> MLLMs have demonstrated remarkable comprehension and reasoning capabilities with complex language and visual data. These advances have spurred the vision of establishing a generalist robotic MLLM proficient in understanding complex human instructions and accomplishing various embodied tasks. However, developing MLLMs for real-world robots is challenging due to the typically limited computation and memory capacities available on robotic platforms. In contrast, the inference of MLLMs involves storing billions of parameters and performing tremendous computation, imposing significant hardware demands. In our paper, we propose a Dynamic Early-Exit Framework for Robotic Vision-Language-Action Model (DeeR-VLA, or simply DeeR) that automatically adjusts the size of the activated MLLM based on each situation at hand. The approach leverages a multi-exit architecture in MLLMs, which allows the model to terminate processing once a proper size of the model has been activated for a specific situation, thus avoiding further redundant computation. Additionally, we develop novel algorithms that establish early-termination criteria for DeeR, conditioned on predefined demands such as average computational cost (i.e., power consumption), as well as peak computational consumption (i.e., latency) and GPU memory usage. These enhancements ensure that DeeR operates efficiently under varying resource constraints while maintaining competitive performance. On the CALVIN robot manipulation benchmark, DeeR demonstrates significant reductions in computational costs of LLM by 5.2-6.5x and GPU memory of LLM by 2-6x without compromising performance. Code and checkpoints are available at https://github.com/yueyang130/DeeR-VLA.

[Arxiv](https://arxiv.org/abs/2411.02359)