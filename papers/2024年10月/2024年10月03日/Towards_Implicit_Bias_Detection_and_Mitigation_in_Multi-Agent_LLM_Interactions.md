# 探索多智能体 LLM 交互中的隐性偏见检测与缓解

发布时间：2024年10月03日

`Agent` `社会研究` `人工智能`

> Towards Implicit Bias Detection and Mitigation in Multi-Agent LLM Interactions

# 摘要

> 随着 LLM 的进步，它们被广泛用于模拟社会和执行多样化的社会任务。然而，由于接触人类数据，LLM 容易受到社会偏见的影响。鉴于 LLM 在社会研究中的应用，减轻这些偏见至关重要。我们的研究探讨了多代理 LLM 交互中的隐性性别偏见，并提出了两种缓解策略。我们首先构建了一个可能出现偏见的情景数据集，并开发了评估偏见的指标。实证分析显示，LLM 的输出中隐性偏见频繁出现（超过 50% 的时间），且在多代理交互后偏见加剧。为此，我们提出了两种策略：通过上下文示例进行自我反思 (ICE) 和监督微调。研究表明，这两种方法均有效减轻偏见，而结合微调和自我反思的方法效果最佳。

> As Large Language Models (LLMs) continue to evolve, they are increasingly being employed in numerous studies to simulate societies and execute diverse social tasks. However, LLMs are susceptible to societal biases due to their exposure to human-generated data. Given that LLMs are being used to gain insights into various societal aspects, it is essential to mitigate these biases. To that end, our study investigates the presence of implicit gender biases in multi-agent LLM interactions and proposes two strategies to mitigate these biases. We begin by creating a dataset of scenarios where implicit gender biases might arise, and subsequently develop a metric to assess the presence of biases. Our empirical analysis reveals that LLMs generate outputs characterized by strong implicit bias associations (>= 50\% of the time). Furthermore, these biases tend to escalate following multi-agent interactions. To mitigate them, we propose two strategies: self-reflection with in-context examples (ICE); and supervised fine-tuning. Our research demonstrates that both methods effectively mitigate implicit biases, with the ensemble of fine-tuning and self-reflection proving to be the most successful.

[Arxiv](https://arxiv.org/abs/2410.02584)