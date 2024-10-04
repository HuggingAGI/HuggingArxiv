# GraphIC：一种基于图的多步推理上下文示例检索模型，专为复杂推理任务设计。

发布时间：2024年10月03日

`LLM应用` `人工智能`

> GraphIC: A Graph-Based In-Context Example Retrieval Model for Multi-Step Reasoning

# 摘要

> ICL 通过在输入中加入少量示例，使 LLM 无需更新参数即可适应新任务。然而，ICL 的效果高度依赖于示例的选择，传统文本嵌入方法在多步骤推理任务（如数学和逻辑问题）中常显不足。这是因为浅层语义相似性无法捕捉深层推理结构。我们提出 GraphIC，一种结合图表示和贝叶斯网络的新方法，用于选择示例。图结构过滤浅层语义，保留核心推理结构，而贝叶斯网络捕捉节点间的依赖关系，与人类认知的层次性相符。这使得 GraphIC 在多步骤推理任务中表现优异。实验证明，GraphIC 在选择示例方面超越了无训练和基于训练的模型，显著提升了 ICL 的性能和互操作性。

> In-context learning (ICL) enables large language models (LLMs) to generalize to new tasks by incorporating a few in-context examples (ICEs) directly in the input, without updating parameters. However, the effectiveness of ICL heavily relies on the selection of ICEs, and conventional text-based embedding methods are often inadequate for tasks that require multi-step reasoning, such as mathematical and logical problem solving. This is due to the bias introduced by shallow semantic similarities that fail to capture the deeper reasoning structures required for these tasks. We present GraphIC, a novel approach that leverages graph-based representations of reasoning processes, coupled with Bayesian Networks (BNs) to select ICEs. Graph structures inherently filter out shallow semantics while preserving the core reasoning structure. Importantly, BNs capture the dependency of a node's attributes on its parent nodes, closely mirroring the hierarchical nature of human cognition-where each thought is shaped by preceding ones. This makes BNs particularly well-suited for multi-step reasoning tasks, aligning the process more closely with human-like reasoning. Extensive experiments across three types of reasoning tasks (mathematical reasoning, code generation, and logical reasoning) demonstrate that GraphIC outperforms both training-free and training-based models in selecting ICEs, excelling in terms of both effectiveness and efficiency. We show that GraphIC enhances ICL's performance and interoperability, significantly advancing ICE selection for multi-step reasoning tasks.

[Arxiv](https://arxiv.org/abs/2410.02203)