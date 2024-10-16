# NesTools：专为评估大型语言模型嵌套工具学习能力而设计的数据集

发布时间：2024年10月15日

`LLM应用` `人工智能` `软件开发`

> NesTools: A Dataset for Evaluating Nested Tool Learning Abilities of Large Language Models

# 摘要

> 大型语言模型 (LLM) 与工具学习的结合在实际应用中表现出色。然而，当前研究对 LLM 在嵌套工具调用中的能力探索不足，主要因为缺乏相关数据。为此，我们推出了 NesTools，通过自动生成和人工优化，构建了高质量的嵌套工具调用数据集，旨在为 LLM 的嵌套工具学习能力提供新的评估基准。实验结果表明，尽管 LLM 在许多任务中表现优异，但在复杂的嵌套工具学习任务中仍有提升空间。

> Large language models (LLMs) combined with tool learning have gained impressive results in real-world applications. During tool learning, LLMs may call multiple tools in nested orders, where the latter tool call may take the former response as its input parameters. However, current research on the nested tool learning capabilities is still under-explored, since the existing benchmarks lack of relevant data instances. To address this problem, we introduce NesTools to bridge the current gap in comprehensive nested tool learning evaluations. NesTools comprises a novel automatic data generation method to construct large-scale nested tool calls with different nesting structures. With manual review and refinement, the dataset is in high quality and closely aligned with real-world scenarios. Therefore, NesTools can serve as a new benchmark to evaluate the nested tool learning abilities of LLMs. We conduct extensive experiments on 22 LLMs, and provide in-depth analyses with NesTools, which shows that current LLMs still suffer from the complex nested tool learning task.

[Arxiv](https://arxiv.org/abs/2410.11805)