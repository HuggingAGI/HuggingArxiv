# DynamicER：为 RAG 系统解析新兴提及并映射到动态实体

发布时间：2024年10月15日

`RAG` `知识库` `问答系统`

> DynamicER: Resolving Emerging Mentions to Dynamic Entities for RAG

# 摘要

> 在语言快速变化的今天，解决新表达在不断更新的知识库中的问题依然棘手。特别是在知识库增强的生成（RAG）中，新兴表达阻碍了相关文档的检索，导致生成器产生幻觉。为此，我们提出了一项新任务，旨在解决新兴提及到动态实体的问题，并推出了DynamicER基准。该基准包括动态实体提及解析和知识密集型问答任务，分别评估实体链接和RAG模型对新表达的适应性。我们发现，现有模型在处理这些新表达时表现不佳。因此，我们提出了一种时间分段聚类方法，结合持续适应，有效应对实体演变和新兴提及的时间动态。实验结果显示，我们的方法显著提升了RAG模型在问答任务中的表现。

> In the rapidly evolving landscape of language, resolving new linguistic expressions in continuously updating knowledge bases remains a formidable challenge. This challenge becomes critical in retrieval-augmented generation (RAG) with knowledge bases, as emerging expressions hinder the retrieval of relevant documents, leading to generator hallucinations. To address this issue, we introduce a novel task aimed at resolving emerging mentions to dynamic entities and present DynamicER benchmark. Our benchmark includes dynamic entity mention resolution and entity-centric knowledge-intensive QA task, evaluating entity linking and RAG model's adaptability to new expressions, respectively. We discovered that current entity linking models struggle to link these new expressions to entities. Therefore, we propose a temporal segmented clustering method with continual adaptation, effectively managing the temporal dynamics of evolving entities and emerging mentions. Extensive experiments demonstrate that our method outperforms existing baselines, enhancing RAG model performance on QA task with resolved mentions.

[Arxiv](https://arxiv.org/abs/2410.11494)