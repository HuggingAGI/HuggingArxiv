# 聚焦型大型语言模型展现出稳定的多次学习能力。

发布时间：2024年08月25日

`LLM应用` `人工智能`

> Focused Large Language Models are Stable Many-Shot Learners

# 摘要

> ICL 通过学习演示，助力 LLMs 快速适应新任务。然而，随着上下文长度的增加，ICL 在多-shot 场景下的表现并未同步提升。我们发现，过多的演示会分散模型对关键信息的注意力。借鉴人类学习模式，我们创新了无需训练的 FocusICL 方法，通过琐碎性过滤和分层注意力机制，确保模型专注于重要内容。此外，我们基于演示的模型困惑度，设计了高效的超参数搜索策略。实验证明，FocusICL 不仅提升了 5.2% 的平均性能，还能在多-shot 环境下稳定发挥。

> In-Context Learning (ICL) enables large language models (LLMs) to achieve rapid task adaptation by learning from demonstrations. With the increase in available context length of LLMs, recent experiments have shown that the performance of ICL does not necessarily scale well in many-shot (demonstration) settings. We theoretically and experimentally confirm that the reason lies in more demonstrations dispersing the model attention from the query, hindering its understanding of key content. Inspired by how humans learn from examples, we propose a training-free method FocusICL, which conducts triviality filtering to avoid attention being diverted by unimportant contents at token-level and operates hierarchical attention to further ensure sufficient attention towards current query at demonstration-level. We also design an efficient hyperparameter searching strategy for FocusICL based on model perplexity of demonstrations. Comprehensive experiments validate that FocusICL achieves an average performance improvement of 5.2% over vanilla ICL and scales well with many-shot demonstrations.

[Arxiv](https://arxiv.org/abs/2408.13987)