# 探究 LLM 机器翻译中上下文的影响

发布时间：2024年10月21日

`LLM应用` `机器翻译`

> Analyzing Context Contributions in LLM-based Machine Translation

# 摘要

> LLM 在机器翻译中表现卓越，并通过少样本示例展示了强大的上下文学习能力。然而，LLM 如何利用输入上下文的不同部分仍待深入研究。我们全面分析了 MT 中的上下文利用，发现：(1) 少样本示例的源部分贡献更大，不受翻译方向影响；(2) 平行数据微调改变了上下文贡献模式；(3) 早期少样本示例对翻译序列的贡献更高。此外，异常上下文贡献可能揭示病态翻译。这些发现揭示了 LLM 在 MT 中的独特机制，超越了传统编码器-解码器模型的认知。

> Large language models (LLMs) have achieved state-of-the-art performance in machine translation (MT) and demonstrated the ability to leverage in-context learning through few-shot examples. However, the mechanisms by which LLMs use different parts of the input context remain largely unexplored. In this work, we provide a comprehensive analysis of context utilization in MT, studying how LLMs use various context parts, such as few-shot examples and the source text, when generating translations. We highlight several key findings: (1) the source part of few-shot examples appears to contribute more than its corresponding targets, irrespective of translation direction; (2) finetuning LLMs with parallel data alters the contribution patterns of different context parts; and (3) there is a positional bias where earlier few-shot examples have higher contributions to the translated sequence. Finally, we demonstrate that inspecting anomalous context contributions can potentially uncover pathological translations, such as hallucinations. Our findings shed light on the internal workings of LLM-based MT which go beyond those known for standard encoder-decoder MT models.

[Arxiv](https://arxiv.org/abs/2410.16246)