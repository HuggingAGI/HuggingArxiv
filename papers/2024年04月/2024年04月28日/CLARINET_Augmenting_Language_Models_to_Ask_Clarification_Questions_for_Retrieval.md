# CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索

发布时间：2024年04月28日

`RAG

理由：这篇论文主要探讨了在信息检索场景中如何通过提出澄清问题来优化检索模型的性能。论文中提到的CLARINET系统通过增强大型语言模型（LLM）以考虑检索分布，并进行端到端微调，生成有助于确定正确候选答案的澄清问题。这种方法属于检索增强生成（RAG）的范畴，因为它结合了检索和生成技术来提高信息检索的准确性。因此，这篇论文应归类于RAG。` `信息检索`

> CLARINET: Augmenting Language Models to Ask Clarification Questions for Retrieval

# 摘要

> 用户常提出模糊不清的请求，需要进一步澄清。我们探讨了在信息检索场景中如何提出澄清问题，这一挑战在于如何将检索模型中的不确定性转化为自然语言问题。为此，我们开发了CLARINET系统，它能提出有助于确定正确候选答案的澄清问题。通过增强LLM以考虑检索分布，并进行端到端微调，我们的系统能生成提升真实候选者排名的问句。在实际的书籍搜索数据集测试中，CLARINET在检索成功率上超越了传统启发式方法17%，并比未优化的LLM提升了39%。

> Users often make ambiguous requests that require clarification. We study the problem of asking clarification questions in an information retrieval setting, where systems often face ambiguous search queries and it is challenging to turn the uncertainty in the retrieval model into a natural language question. We present CLARINET, a system that asks informative clarification questions by choosing questions whose answers would maximize certainty in the correct candidate. Our approach works by augmenting a large language model (LLM) to condition on a retrieval distribution, finetuning end-to-end to generate the question that would have maximized the rank of the true candidate at each turn. When evaluated on a real-world retrieval dataset of users searching for books, our system outperforms traditional heuristics such as information gain on retrieval success by 17% and vanilla-prompted LLMs by 39% relative.

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x1.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x2.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x3.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x4.png)

![CLARINET：赋能语言模型，通过提问澄清问题来优化信息检索](../../../paper_images/2405.15784/x5.png)

[Arxiv](https://arxiv.org/abs/2405.15784)