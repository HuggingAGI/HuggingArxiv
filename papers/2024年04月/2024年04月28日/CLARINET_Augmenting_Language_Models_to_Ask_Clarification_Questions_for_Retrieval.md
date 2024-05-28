# CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索

发布时间：2024年04月28日

`RAG

理由：这篇论文介绍了一个名为CLARINET的系统，该系统通过增强大型语言模型（LLM）来提出澄清问题，以帮助在信息检索场景中确定正确的候选答案。这个系统特别关注于如何将模型中的不确定性转化为自然语言问题，并通过端到端微调来优化问题生成。这与RAG（Retrieval-Augmented Generation）的概念相符，因为它结合了检索和生成过程来提高信息检索的性能。因此，这篇论文更适合归类于RAG。` `信息检索`

> CLARINET: Augmenting Language Models to Ask Clarification Questions for Retrieval

# 摘要

> 用户常提出模糊不清的请求，需要进一步澄清。我们探讨了在信息检索场景中如何提出澄清问题，这一过程因系统常遇到模糊查询而变得复杂，且将模型中的不确定性转化为自然语言问题颇具挑战。为此，我们开发了CLARINET系统，它能提出有助于确定正确候选答案的澄清问题。该系统通过增强大型语言模型（LLM），使其根据检索结果分布进行调整，并进行端到端微调，以生成每个阶段最有可能提升正确答案排名的问题。在实际的书籍搜索数据集测试中，CLARINET在检索成功率上比传统启发式方法高出17%，比未优化的LLMs高出39%。

> Users often make ambiguous requests that require clarification. We study the problem of asking clarification questions in an information retrieval setting, where systems often face ambiguous search queries and it is challenging to turn the uncertainty in the retrieval model into a natural language question. We present CLARINET, a system that asks informative clarification questions by choosing questions whose answers would maximize certainty in the correct candidate. Our approach works by augmenting a large language model (LLM) to condition on a retrieval distribution, finetuning end-to-end to generate the question that would have maximized the rank of the true candidate at each turn. When evaluated on a real-world retrieval dataset of users searching for books, our system outperforms traditional heuristics such as information gain on retrieval success by 17% and vanilla-prompted LLMs by 39% relative.

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x1.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x2.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x3.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x4.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x5.png)

[Arxiv](https://arxiv.org/abs/2405.15784)