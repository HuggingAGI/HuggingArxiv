# 探究现实知识冲突情境下大型语言模型的行为表现

发布时间：2024年04月24日

`分类：RAG` `机器学习`

> Studying Large Language Model Behaviors Under Realistic Knowledge Conflicts

# 摘要

> 检索增强生成（RAG）有效解决了全参数化语言模型的诸多难题，如时间衰减、幻想以及缺乏依据。在RAG模式下，模型能够根据提供的文档上下文更新其知识库。这可能导致模型的固有参数知识与文档中的上下文信息发生冲突，有时模型未必会更新其知识。先前研究通过构建与模型正确参数答案相冲突的合成文档来探讨知识冲突问题。本研究提出了一个更贴近现实的框架，利用真实存在的冲突文档来修正模型中的错误参数知识，从而更真实地模拟知识冲突的产生。研究发现，在这种现实情境下，知识更新的失败率低于先前的研究结果。当模型未能更新答案时，存在一种参数偏好：上下文中出现的错误参数答案会增加知识更新失败的风险。这些发现暗示大型语言模型（LLMs）的事实性参数知识可能对其阅读理解能力产生负面影响。相关代码已在 https://github.com/kortukov/realistic_knowledge_conflicts/ 上公开。

> Retrieval-augmented generation (RAG) mitigates many problems of fully parametric language models, such as temporal degradation, hallucinations, and lack of grounding. In RAG, the model's knowledge can be updated from documents provided in context. This leads to cases of conflict between the model's parametric knowledge and the contextual information, where the model may not always update its knowledge. Previous work studied knowledge conflicts by creating synthetic documents that contradict the model's correct parametric answers. We present a framework for studying knowledge conflicts in a realistic setup. We update incorrect parametric knowledge using real conflicting documents. This reflects how knowledge conflicts arise in practice. In this realistic scenario, we find that knowledge updates fail less often than previously reported. In cases where the models still fail to update their answers, we find a parametric bias: the incorrect parametric answer appearing in context makes the knowledge update likelier to fail. These results suggest that the factual parametric knowledge of LLMs can negatively influence their reading abilities and behaviors. Our code is available at https://github.com/kortukov/realistic_knowledge_conflicts/.

[Arxiv](https://arxiv.org/abs/2404.16032)