# 运用大型语言模型来实现多模态搜索。

发布时间：2024年04月24日

`LLM应用` `电子商务` `搜索技术`

> Leveraging Large Language Models for Multimodal Search

# 摘要

> 多模态搜索正日益成为用户表达搜索意图的自然而有效手段。它通过图像展示产品细节，文本则简化了搜索条件的调整。尽管如此，现有系统中的不稳定性和对简单查询的无效响应仍是挑战。尤其是面对自然语言查询的多样性，其中可能包含含糊、隐含或无关的信息，这些挑战尤为突出。为了应对这些问题，我们需要构建具备更强大的匹配功能、推理能力和能够感知上下文的查询解析及重写的系统。本文提出了一种创新的多模态搜索模型，它在Fashion200K数据集上创下了新的性能记录。我们还设计了一种新的搜索界面，整合了大型语言模型（LLMs），以促进与用户的自然语言互动。这个界面在与用户进行对话式互动的同时，会将查询引导至搜索系统，并考虑用户之前的搜索历史。结合我们的多模态搜索模型，它标志着购物助手领域迈入了一个新的时代，能够提供更人性化的交互体验，提升搜索的全面感受。

> Multimodal search has become increasingly important in providing users with a natural and effective way to ex-press their search intentions. Images offer fine-grained details of the desired products, while text allows for easily incorporating search modifications. However, some existing multimodal search systems are unreliable and fail to address simple queries. The problem becomes harder with the large variability of natural language text queries, which may contain ambiguous, implicit, and irrelevant in-formation. Addressing these issues may require systems with enhanced matching capabilities, reasoning abilities, and context-aware query parsing and rewriting. This paper introduces a novel multimodal search model that achieves a new performance milestone on the Fashion200K dataset. Additionally, we propose a novel search interface integrating Large Language Models (LLMs) to facilitate natural language interaction. This interface routes queries to search systems while conversationally engaging with users and considering previous searches. When coupled with our multimodal search model, it heralds a new era of shopping assistants capable of offering human-like interaction and enhancing the overall search experience.

![运用大型语言模型来实现多模态搜索。](../../../paper_images/2404.15790/x2.png)

![运用大型语言模型来实现多模态搜索。](../../../paper_images/2404.15790/success.png)

![运用大型语言模型来实现多模态搜索。](../../../paper_images/2404.15790/failures.png)

![运用大型语言模型来实现多模态搜索。](../../../paper_images/2404.15790/demo_example.png)

[Arxiv](https://arxiv.org/abs/2404.15790)