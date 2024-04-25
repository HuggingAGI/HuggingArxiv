# 探究大型语言模型在现实知识冲突场景下的表现

发布时间：2024年04月24日

`RAG` `机器学习`

> Studying Large Language Model Behaviors Under Realistic Knowledge Conflicts

# 摘要

> 检索增强生成技术（RAG）有效缓解了全参数语言模型常见的问题，如信息过时、产生幻觉和缺乏事实依据。在RAG框架下，模型能够根据提供的文档上下文更新其知识库。然而，这也可能引发模型内部参数知识与上下文信息的冲突，导致模型更新知识的频率并不总是如预期那样频繁。先前研究通过构建与模型参数答案相冲突的合成文档来探讨知识冲突问题。本研究提出了一个更贴近现实的框架，利用真实冲突文档修正模型的参数知识错误。研究发现，在现实情境下，知识更新的失败率低于先前的研究结果。当模型未能更新答案时，存在一种参数偏好：上下文中出现的不正确参数答案增加了知识更新失败的风险。这些发现暗示了大型语言模型（LLMs）的事实性参数知识可能会对其阅读理解和行为产生负面效应。相关代码已在 https://github.com/kortukov/realistic_knowledge_conflicts/ 上公开。

> Retrieval-augmented generation (RAG) mitigates many problems of fully parametric language models, such as temporal degradation, hallucinations, and lack of grounding. In RAG, the model's knowledge can be updated from documents provided in context. This leads to cases of conflict between the model's parametric knowledge and the contextual information, where the model may not always update its knowledge. Previous work studied knowledge conflicts by creating synthetic documents that contradict the model's correct parametric answers. We present a framework for studying knowledge conflicts in a realistic setup. We update incorrect parametric knowledge using real conflicting documents. This reflects how knowledge conflicts arise in practice. In this realistic scenario, we find that knowledge updates fail less often than previously reported. In cases where the models still fail to update their answers, we find a parametric bias: the incorrect parametric answer appearing in context makes the knowledge update likelier to fail. These results suggest that the factual parametric knowledge of LLMs can negatively influence their reading abilities and behaviors. Our code is available at https://github.com/kortukov/realistic_knowledge_conflicts/.

[Arxiv](https://arxiv.org/abs/2404.16032)