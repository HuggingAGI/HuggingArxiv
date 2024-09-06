# 大型语言模型中少样本学习与微调的表示图景

发布时间：2024年09月05日

`LLM理论` `人工智能`

> The representation landscape of few-shot learning and fine-tuning in large language models

# 摘要

> ICL 和 SFT 是提升 LLM 特定任务性能的两种常见策略，尽管性质不同，但都能带来相似的性能提升。然而，它们在 LLM 内部是否诱导相似的表示仍是个谜。我们通过分析隐藏表示的概率景观来探讨这一问题。研究发现，ICL 和 SFT 在网络中间都经历了急剧转变，但创建的内部结构截然不同。ICL 在前半部分形成语义分层的可解释表示，而 SFT 则显得模糊且语义混合。在后半部分，SFT 的表示更好地编码了答案身份，而 ICL 的表示则显得更为模糊。这一发现揭示了 LLM 在不同条件下解决任务时的多样化策略，为我们设计从语言模型中提取信息的最佳方法提供了新的思路。

> In-context learning (ICL) and supervised fine-tuning (SFT) are two common strategies for improving the performance of modern large language models (LLMs) on specific tasks. Despite their different natures, these strategies often lead to comparable performance gains. However, little is known about whether they induce similar representations inside LLMs. We approach this problem by analyzing the probability landscape of their hidden representations in the two cases. More specifically, we compare how LLMs solve the same question-answering task, finding that ICL and SFT create very different internal structures, in both cases undergoing a sharp transition in the middle of the network. In the first half of the network, ICL shapes interpretable representations hierarchically organized according to their semantic content. In contrast, the probability landscape obtained with SFT is fuzzier and semantically mixed. In the second half of the model, the fine-tuned representations develop probability modes that better encode the identity of answers, while the landscape of ICL representations is characterized by less defined peaks. Our approach reveals the diverse computational strategies developed inside LLMs to solve the same task across different conditions, allowing us to make a step towards designing optimal methods to extract information from language models.

[Arxiv](https://arxiv.org/abs/2409.03662)