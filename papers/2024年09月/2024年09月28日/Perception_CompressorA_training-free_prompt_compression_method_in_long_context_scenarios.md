# 感知压缩器：长上下文场景中的无训练提示压缩法

发布时间：2024年09月28日

`LLM应用` `人工智能`

> Perception Compressor:A training-free prompt compression method in long context scenarios

# 摘要

> LLM 在多种场景中表现出色，但在长上下文场景中，冗余信息过多且容易迷失，导致性能下降。为此，我们推出了感知压缩器，一种无需训练的提示压缩方法。它通过双斜率比率分配器动态调整压缩和开放比率，利用引导问题和指令的感知检索器提取最相关信息，并通过半引导迭代压缩去除干扰标记，保留关键信息。实验结果表明，感知压缩器在 NaturalQuestions、LongBench 和 MuSiQue 等长上下文基准测试中，显著超越现有方法，达到行业领先水平。

> Large Language Models (LLMs) demonstrate exceptional capabilities in various scenarios. However, they suffer from much redundant information and tend to be lost in the middle in long context scenarios, leading to inferior performance. To address these challenges, we present Perception Compressor, a training-free prompt compression method. It includes a dual-slope ratio allocator to dynamically assign compression ratios and open-book ratios, a perception retriever that leverages guiding questions and instruction to retrieve the most relevant demonstrations, and a semi-guided iterative compression that retains key information at the token level while removing tokens that distract the LLM. We conduct extensive experiments on long context benchmarks, i.e., NaturalQuestions, LongBench, and MuSiQue. Experiment results show that Perception Compressor outperforms existing methods by a large margin, achieving state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2409.19272)