# 骆驼骑士：让开源巨型语言模型适应低资源语言的挑战

发布时间：2024年05月13日

`LLM理论

这篇论文探讨了如何调整以英语训练的大型语言模型以适应低资源语言，并研究了多种策略的效果。这属于对大型语言模型（LLM）的理论研究，因为它关注的是模型的适应性和性能优化，而不是具体的应用场景或Agent的设计。因此，它更符合LLM理论这一分类。` `多语言技术`

> LlamaTurk: Adapting Open-Source Generative Large Language Models for Low-Resource Language

# 摘要

> 尽管英语主导的生成式大型语言模型取得了显著进展，但为了提升全球语言的可访问性，对低资源语言的进一步开发仍是迫切需要的。当前，单语和多语预训练是处理这些语言的主要手段，但前者因硬件需求而昂贵，后者则在不同语言间表现参差不齐。本研究提出了一种新思路，即对以英语训练的大型语言模型进行调整，以适应低资源语言。我们探讨了多种策略，如持续训练、指令微调、任务特定微调及词汇扩展。研究结果表明，持续训练有助于提升语言理解，这在困惑度上有所体现，而任务特定微调则普遍增强了下游任务的表现。然而，词汇扩展并未带来显著益处。此外，尽管大型模型通过少量样本微调提升了任务性能，但多语模型在适应后，其表现却不及单语模型。

> Despite advancements in English-dominant generative large language models, further development is needed for low-resource languages to enhance global accessibility. The primary methods for representing these languages are monolingual and multilingual pretraining. Monolingual pretraining is expensive due to hardware requirements, and multilingual models often have uneven performance across languages. This study explores an alternative solution by adapting large language models, primarily trained on English, to low-resource languages. We assess various strategies, including continual training, instruction fine-tuning, task-specific fine-tuning, and vocabulary extension. The results show that continual training improves language comprehension, as reflected in perplexity scores, and task-specific tuning generally enhances performance of downstream tasks. However, extending the vocabulary shows no substantial benefits. Additionally, while larger models improve task performance with few-shot tuning, multilingual models perform worse than their monolingual counterparts when adapted.

[Arxiv](https://arxiv.org/abs/2405.07745)