# 法律领域中大型语言模型的事实性

发布时间：2024年09月18日

`LLM应用` `人工智能`

> The Factuality of Large Language Models in the Legal Domain

# 摘要

> 本文探讨了 LLM 在法律领域作为知识库的事实性，允许答案有合理变体，并在不确定时让模型拒绝回答。我们设计了一个涵盖案例法和立法的多样化问题数据集，并通过精确、别名和模糊匹配等方法评估了多个 LLM。结果表明，别名和模糊匹配显著提升了性能。我们还发现，拒绝回答和上下文示例都能提高准确性。最后，通过在法律文档上的额外预训练，如 SaulLM 所展示的，事实准确性从 63% 提升至 81%。

> This paper investigates the factuality of large language models (LLMs) as knowledge bases in the legal domain, in a realistic usage scenario: we allow for acceptable variations in the answer, and let the model abstain from answering when uncertain. First, we design a dataset of diverse factual questions about case law and legislation. We then use the dataset to evaluate several LLMs under different evaluation methods, including exact, alias, and fuzzy matching. Our results show that the performance improves significantly under the alias and fuzzy matching methods. Further, we explore the impact of abstaining and in-context examples, finding that both strategies enhance precision. Finally, we demonstrate that additional pre-training on legal documents, as seen with SaulLM, further improves factual precision from 63% to 81%.

[Arxiv](https://arxiv.org/abs/2409.11798)