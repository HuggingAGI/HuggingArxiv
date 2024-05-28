# CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索

发布时间：2024年04月28日

`RAG

这篇论文主要探讨了在信息检索场景中如何通过提出澄清问题来处理模糊查询，并开发了CLARINET系统来增强大型语言模型（LLM）以生成有助于确定正确候选答案的澄清问题。这种方法涉及对LLM的微调和优化，以提高信息检索的效率和准确性。因此，它更符合RAG分类，即检索增强生成（Retrieval-Augmented Generation），这是一种结合了检索和生成技术的方法，用于改进语言模型的应用性能。` `信息检索`

> CLARINET: Augmenting Language Models to Ask Clarification Questions for Retrieval

# 摘要

> 用户常提出模糊不清的请求，需进一步澄清。我们探讨了在信息检索场景中如何提出澄清问题，面对模糊查询，系统需将模型中的不确定性转化为自然语言问题，这颇具挑战。为此，我们开发了CLARINET系统，它能提出有助于确定正确候选答案的澄清问题。该系统通过增强大型语言模型（LLM），使其基于检索结果进行微调，从而生成能提升正确答案排名的问题。在实际的书籍搜索数据集测试中，CLARINET在检索成功率上比传统启发式方法高出17%，比未优化的LLMs高出39%。

> Users often make ambiguous requests that require clarification. We study the problem of asking clarification questions in an information retrieval setting, where systems often face ambiguous search queries and it is challenging to turn the uncertainty in the retrieval model into a natural language question. We present CLARINET, a system that asks informative clarification questions by choosing questions whose answers would maximize certainty in the correct candidate. Our approach works by augmenting a large language model (LLM) to condition on a retrieval distribution, finetuning end-to-end to generate the question that would have maximized the rank of the true candidate at each turn. When evaluated on a real-world retrieval dataset of users searching for books, our system outperforms traditional heuristics such as information gain on retrieval success by 17% and vanilla-prompted LLMs by 39% relative.

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x1.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x2.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x3.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x4.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x5.png)

[Arxiv](https://arxiv.org/abs/2405.15784)