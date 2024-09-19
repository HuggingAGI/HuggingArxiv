# 从列表到表情符号：格式偏差如何影响模型对齐

发布时间：2024年09月18日

`LLM理论` `人工智能`

> From Lists to Emojis: How Format Bias Affects Model Alignment

# 摘要

> 本文探讨了 RLHF 中的格式偏差。我们发现，包括人类评估者和 GPT-4 在内的多种偏好模型，对列表、链接、粗体文本和表情符号等特定格式有强烈偏好。大型语言模型（LLM）利用这些偏差，在 AlpacaEval 和 LMSYS Chatbot Arena 等基准测试中取得更高排名。例如，当前偏好模型更青睐冗长的响应，即使其质量不如更简洁的回答。然而，除了冗长之外的格式偏差研究仍显不足。我们扩展了偏好学习中的偏差研究，涵盖了更广泛的格式偏差，并发现仅需少量偏差数据（少于 1%）即可显著影响奖励模型。此外，下游对齐算法如 best-of-n 采样和在线迭代 DPO 也容易受到这些格式偏差的影响。我们的研究强调，在设计和评估模型时，必须区分格式和内容。

> In this paper, we study format biases in reinforcement learning from human feedback (RLHF). We observe that many widely-used preference models, including human evaluators, GPT-4, and top-ranking models on the RewardBench benchmark, exhibit strong biases towards specific format patterns, such as lists, links, bold text, and emojis. Furthermore, large language models (LLMs) can exploit these biases to achieve higher rankings on popular benchmarks like AlpacaEval and LMSYS Chatbot Arena. One notable example of this is verbosity bias, where current preference models favor longer responses that appear more comprehensive, even when their quality is equal to or lower than shorter, competing responses. However, format biases beyond verbosity remain largely underexplored in the literature. In this work, we extend the study of biases in preference learning beyond the commonly recognized length bias, offering a comprehensive analysis of a wider range of format biases. Additionally, we show that with a small amount of biased data (less than 1%), we can inject significant bias into the reward model. Moreover, these format biases can also be easily exploited by downstream alignment algorithms, such as best-of-n sampling and online iterative DPO, as it is usually easier to manipulate the format than to improve the quality of responses. Our findings emphasize the need to disentangle format and content both for designing alignment algorithms and evaluating models.

[Arxiv](https://arxiv.org/abs/2409.11704)