# LongRecipe：大型语言模型中高效长上下文泛化的秘方

发布时间：2024年08月31日

`LLM理论` `人工智能` `计算机科学`

> LongRecipe: Recipe for Efficient Long Context Generalization in Large Languge Models

# 摘要

> 大型语言模型（LLM）在处理长上下文任务时，因预训练中的有效上下文窗口有限而面临挑战。为此，我们推出了 **LongRecipe**，一种高效策略，通过标记分析、位置索引转换及训练优化，扩展 LLM 的上下文窗口。实验显示，LongRecipe 在保持高效训练的同时，显著提升模型对长序列的理解，仅需目标窗口的 30% 大小，并节省超过 85% 的计算资源。此外，它还保留了 LLM 在常规任务中的原有能力。最终，我们能将开源 LLM 的上下文窗口从 8k 扩展至 128k，仅用单个 80G GPU 一天训练，性能接近 GPT-4。代码已发布于 [链接](https://github.com/zhiyuanhubj/LongRecipe)。

> Large language models (LLMs) face significant challenges in handling long-context tasks because of their limited effective context window size during pretraining, which restricts their ability to generalize over extended sequences. Meanwhile, extending the context window in LLMs through post-pretraining is highly resource-intensive. To address this, we introduce **LongRecipe**, an efficient training strategy for extending the context window of LLMs, including impactful token analysis, position index transformation, and training optimization strategies. It simulates long-sequence inputs while maintaining training efficiency and significantly improves the model's understanding of long-range dependencies. Experiments on three types of LLMs show that LongRecipe can utilize long sequences while requiring only 30% of the target context window size, and reduces computational training resource over 85% compared to full sequence training. Furthermore, LongRecipe also preserves the original LLM's capabilities in general tasks. Ultimately, *we can extend the effective context window of open-source LLMs from 8k to 128k, achieving performance close to GPT-4 with just one day of dedicated training using a single GPU with 80G memory.* Our code is released at the [link](https://github.com/zhiyuanhubj/LongRecipe).

[Arxiv](https://arxiv.org/abs/2409.00509)