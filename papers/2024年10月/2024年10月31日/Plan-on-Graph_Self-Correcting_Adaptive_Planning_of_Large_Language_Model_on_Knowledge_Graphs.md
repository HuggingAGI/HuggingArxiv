# 图上规划：大型语言模型在知识图谱上的自校正自适应规划

发布时间：2024年10月31日

`LLM应用` `知识图谱` `大型语言模型`

> Plan-on-Graph: Self-Correcting Adaptive Planning of Large Language Model on Knowledge Graphs

# 摘要

> 大型语言模型（LLMs）在复杂任务上已经展现出了卓越的推理能力，但它们仍然存在知识过时、幻觉和决策不透明的问题。相比之下，知识图谱（KGs）可以为大型语言模型提供明确且可编辑的知识，以缓解这些问题。现有的知识图谱增强型大型语言模型范式手动预先定义探索空间的广度，并要求在知识图谱中完美导航。然而，这种范式不能根据问题语义自适应地探索知识图谱中的推理路径，也不能自我纠正错误的推理路径，从而导致效率和效果上的瓶颈。为了解决这些限制，我们提出了一种用于知识图谱增强型大型语言模型的新型自我纠正自适应规划范式，名为图上规划（PoG），它首先将问题分解为几个子目标，然后重复自适应探索推理路径、更新内存和反思是否需要自我纠正错误推理路径的过程，直到得出答案。具体来说，设计了指导、内存和反思这三个重要机制协同工作，以保证图推理的自我纠正规划的自适应广度。最后，在三个真实世界数据集上进行的大量实验证明了 PoG 的有效性和效率。

> Large Language Models (LLMs) have shown remarkable reasoning capabilities on complex tasks, but they still suffer from out-of-date knowledge, hallucinations, and opaque decision-making. In contrast, Knowledge Graphs (KGs) can provide explicit and editable knowledge for LLMs to alleviate these issues. Existing paradigm of KG-augmented LLM manually predefines the breadth of exploration space and requires flawless navigation in KGs. However, this paradigm cannot adaptively explore reasoning paths in KGs based on the question semantics and self-correct erroneous reasoning paths, resulting in a bottleneck in efficiency and effect. To address these limitations, we propose a novel self-correcting adaptive planning paradigm for KG-augmented LLM named Plan-on-Graph (PoG), which first decomposes the question into several sub-objectives and then repeats the process of adaptively exploring reasoning paths, updating memory, and reflecting on the need to self-correct erroneous reasoning paths until arriving at the answer. Specifically, three important mechanisms of Guidance, Memory, and Reflection are designed to work together, to guarantee the adaptive breadth of self-correcting planning for graph reasoning. Finally, extensive experiments on three real-world datasets demonstrate the effectiveness and efficiency of PoG.

[Arxiv](https://arxiv.org/abs/2410.23875)