# 探索大型语言模型在电影情节概要中叙事推理的局限

发布时间：2024年09月22日

`LLM应用` `人工智能`

> Unveiling Narrative Reasoning Limits of Large Language Models with Trope in Movie Synopses

# 摘要

> 配备 CoT 的大型语言模型在数学、常识和逻辑等事实内容中表现出色，但在需要高度抽象能力的叙事推理中，其表现尚未被深入研究。本研究通过电影梗概中的套路来测试最先进 LLMs 的抽象推理能力，发现其表现不佳。为此，我们提出了一种套路查询方法，成功将 F1 分数提升了 11.8 分。此外，尽管 CoT 被认为能增强多步骤推理，但本研究发现它在叙事内容中可能导致幻觉，影响 GPT-4 的性能。我们还设计了一种对抗性注入方法，在不显式使用套路的情况下，将相关文本标记嵌入电影梗概，揭示了 CoT 对这种嵌入的高度敏感性。我们的全面分析为未来研究提供了新的视角。

> Large language models (LLMs) equipped with chain-of-thoughts (CoT) prompting have shown significant multi-step reasoning capabilities in factual content like mathematics, commonsense, and logic. However, their performance in narrative reasoning, which demands greater abstraction capabilities, remains unexplored. This study utilizes tropes in movie synopses to assess the abstract reasoning abilities of state-of-the-art LLMs and uncovers their low performance. We introduce a trope-wise querying approach to address these challenges and boost the F1 score by 11.8 points. Moreover, while prior studies suggest that CoT enhances multi-step reasoning, this study shows CoT can cause hallucinations in narrative content, reducing GPT-4's performance. We also introduce an Adversarial Injection method to embed trope-related text tokens into movie synopses without explicit tropes, revealing CoT's heightened sensitivity to such injections. Our comprehensive analysis provides insights for future research directions.

[Arxiv](https://arxiv.org/abs/2409.14324)