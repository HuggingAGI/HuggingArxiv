# 优化用于推理的语言模型，是否还保留着自回归的痕迹？本文将深入分析 OpenAI o1 的这一特性。

发布时间：2024年10月02日

`LLM理论` `人工智能`

> When a language model is optimized for reasoning, does it still show embers of autoregression? An analysis of OpenAI o1

# 摘要

> 在《Embers of Autoregression》（McCoy et al., 2023）中，我们揭示了多个大型语言模型（LLMs）因源于下一个词预测而存在的重要局限。本文探讨了这些局限是否在o1中依然存在，o1是OpenAI推出的新系统，专为推理优化。研究发现，o1在许多任务上显著超越了以往的LLMs，尤其是在常见任务的罕见变体上（如从每个词的第二个字母而非第一个字母形成缩写）。尽管在定量上有所提升，o1仍表现出与先前系统相同的定性特征：对示例和任务的概率敏感，高概率情境下表现更佳且所需“思考标记”更少。这表明，尽管推理优化能缓解语言模型的概率敏感性，但可能无法彻底消除。

> In "Embers of Autoregression" (McCoy et al., 2023), we showed that several large language models (LLMs) have some important limitations that are attributable to their origins in next-word prediction. Here we investigate whether these issues persist with o1, a new system from OpenAI that differs from previous LLMs in that it is optimized for reasoning. We find that o1 substantially outperforms previous LLMs in many cases, with particularly large improvements on rare variants of common tasks (e.g., forming acronyms from the second letter of each word in a list, rather than the first letter). Despite these quantitative improvements, however, o1 still displays the same qualitative trends that we observed in previous systems. Specifically, o1 - like previous LLMs - is sensitive to the probability of examples and tasks, performing better and requiring fewer "thinking tokens" in high-probability settings than in low-probability ones. These results show that optimizing a language model for reasoning can mitigate but might not fully overcome the language model's probability sensitivity.

[Arxiv](https://arxiv.org/abs/2410.01792)