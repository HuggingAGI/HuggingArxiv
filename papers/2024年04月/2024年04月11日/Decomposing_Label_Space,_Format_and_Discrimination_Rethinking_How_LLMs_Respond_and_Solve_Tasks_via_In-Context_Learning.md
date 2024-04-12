# 解构标签空间、格式与歧视现象：深入探讨大型语言模型（LLM）通过上下文学习应对与解决问题的机制。

发布时间：2024年04月11日

`LLM理论` `语言模型` `上下文学习`

> Decomposing Label Space, Format and Discrimination: Rethinking How LLMs Respond and Solve Tasks via In-Context Learning

# 摘要

> 随着大型语言模型（LLMs）的壮大，上下文学习（ICL）展现出其强大的实力。通过少量示例引导，ICL赋予LLMs执行众多任务的能力，无需调整数以百万计的参数。然而，对于示例如何提升任务表现，目前的研究尚未给出明确答案。本文通过实证分析，将ICL的效能分解为标签空间、格式和辨别力三个层面，并对四种通用LLMs在不同任务上的表现进行了评估。出乎意料的是，示例对提升语言模型的辨识能力作用有限。但ICL在调整标签空间和格式上效果显著，有助于LLMs以恰当的标签词回应。这种能力，犹如为LLMs提供了一份详尽的操作指南。进一步的机制分析揭示，检索与语义最接近的示例能显著增强模型的辨识力。

> In-context Learning (ICL) has emerged as a powerful capability alongside the development of scaled-up large language models (LLMs). By instructing LLMs using few-shot demonstrative examples, ICL enables them to perform a wide range of tasks without updating millions of parameters. However, the precise contributions of demonstrations towards improving end-task performance have not been thoroughly investigated in recent analytical studies. In this paper, we empirically decompose the overall performance of ICL into three dimensions, label space, format, and discrimination, and we evaluate four general-purpose LLMs across a diverse range of tasks. Counter-intuitively, we find that the demonstrations have a marginal impact on provoking discriminative knowledge of language models. However, ICL exhibits significant efficacy in regulating the label space and format which helps LLMs to respond in desired label words. We then demonstrate this ability functions similar to detailed instructions for LLMs to follow. We additionally provide an in-depth analysis of the mechanism of retrieval helping with ICL and find that retrieving the most semantically similar examples notably boosts model's discriminative capability.

[Arxiv](https://arxiv.org/abs/2404.07546)