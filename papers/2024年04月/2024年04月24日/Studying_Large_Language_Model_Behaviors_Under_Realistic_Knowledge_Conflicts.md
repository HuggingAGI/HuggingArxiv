# 探究大型语言模型在现实知识冲突情境下的表现

发布时间：2024年04月24日

`RAG` `机器学习`

> Studying Large Language Model Behaviors Under Realistic Knowledge Conflicts

# 摘要

> 检索增强生成（RAG）有效缓解了全参数化语言模型常见的问题，如信息过时、产生幻觉和缺乏依据。在RAG模式下，模型能够根据提供的文档上下文更新其知识库。然而，这也可能引发模型内部参数知识与文档上下文信息的冲突，导致模型不总是更新其知识库。先前研究通过构建与模型正确参数答案相冲突的合成文档来探讨这种知识冲突。本研究提出了一个更贴近现实的框架，利用真实存在的冲突文档来修正错误的参数知识，从而更真实地模拟知识冲突的发生。研究发现，在现实情境下，知识更新的失败率低于以往研究的报告。当模型未能更新答案时，存在一种参数偏好：如果错误的参数答案出现在上下文中，知识更新更易失败。这些发现暗示大型语言模型（LLMs）的事实性参数知识可能会对其阅读理解和行为产生负面影响。相关代码已在 https://github.com/kortukov/realistic_knowledge_conflicts/ 上公开。

> Retrieval-augmented generation (RAG) mitigates many problems of fully parametric language models, such as temporal degradation, hallucinations, and lack of grounding. In RAG, the model's knowledge can be updated from documents provided in context. This leads to cases of conflict between the model's parametric knowledge and the contextual information, where the model may not always update its knowledge. Previous work studied knowledge conflicts by creating synthetic documents that contradict the model's correct parametric answers. We present a framework for studying knowledge conflicts in a realistic setup. We update incorrect parametric knowledge using real conflicting documents. This reflects how knowledge conflicts arise in practice. In this realistic scenario, we find that knowledge updates fail less often than previously reported. In cases where the models still fail to update their answers, we find a parametric bias: the incorrect parametric answer appearing in context makes the knowledge update likelier to fail. These results suggest that the factual parametric knowledge of LLMs can negatively influence their reading abilities and behaviors. Our code is available at https://github.com/kortukov/realistic_knowledge_conflicts/.

[Arxiv](https://arxiv.org/abs/2404.16032)