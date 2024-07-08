# STOC-TOT：一种结合约束解码的随机思维树方法，专为多跳问答中的复杂推理设计。

发布时间：2024年07月04日

`LLM应用` `问答系统` `人工智能`

> STOC-TOT: Stochastic Tree-of-Thought with Constrained Decoding for Complex Reasoning in Multi-Hop Question Answering

# 摘要

> 多跳问答（MHQA）任务要求模型从多个段落中检索并整合信息，以解答复杂问题。近期研究结合大型语言模型的能力，通过集成证据检索与推理提示（如思维链推理）来提升MHQA的表现。然而，问题类型（如桥梁问题与比较问题）及推理方式（顺序或并行）的多样性，促使我们探索更精细的提示策略，以在零-shot环境下优化MHQA性能。本文提出的STOC-TOT方法，通过随机思维树推理与约束解码，有效应对了这一挑战。我们构建了树状推理结构，引导模型将复杂问题分解为子问题，形成多条推理路径，并在每一步推理中评估各路径的概率。实验结果表明，STOC-TOT在两个MHQA数据集与五个大型语言模型上的表现，均显著超越了现有推理提示方法。

> Multi-hop question answering (MHQA) requires a model to retrieve and integrate information from multiple passages to answer a complex question. Recent systems leverage the power of large language models and integrate evidence retrieval with reasoning prompts (e.g., chain-of-thought reasoning) for the MHQA task. However, the complexities in the question types (bridge v.s. comparison questions) and the reasoning types (sequential v.s. parallel reasonings) require more novel and fine-grained prompting methods to enhance the performance of MHQA under the zero-shot setting. In this paper, we propose STOC-TOT, a stochastic tree-of-thought reasoning prompting method with constrained decoding for MHQA and conduct a detailed comparison with other reasoning prompts on different question types and reasoning types. Specifically, we construct a tree-like reasoning structure by prompting the model to break down the original question into smaller sub-questions to form different reasoning paths. In addition, we prompt the model to provide a probability estimation for each reasoning path at each reasoning step. At answer time, we conduct constrained decoding on the model to generate more grounded answers and reduce hallucination. Experiments comparing STOC-TOT with two MHQA datasets and five large language models showed that our framework outperforms other reasoning prompts by a significant margin.

![STOC-TOT：一种结合约束解码的随机思维树方法，专为多跳问答中的复杂推理设计。](../../../paper_images/2407.03687/MHQA_Example.png)

![STOC-TOT：一种结合约束解码的随机思维树方法，专为多跳问答中的复杂推理设计。](../../../paper_images/2407.03687/Overall_5.png)

![STOC-TOT：一种结合约束解码的随机思维树方法，专为多跳问答中的复杂推理设计。](../../../paper_images/2407.03687/Abl1.png)

![STOC-TOT：一种结合约束解码的随机思维树方法，专为多跳问答中的复杂推理设计。](../../../paper_images/2407.03687/Abl2.png)

![STOC-TOT：一种结合约束解码的随机思维树方法，专为多跳问答中的复杂推理设计。](../../../paper_images/2407.03687/Abl3.png)

[Arxiv](https://arxiv.org/abs/2407.03687)