# Astute RAG：解决大型语言模型中的检索增强缺陷与知识冲突

发布时间：2024年10月09日

`RAG` `人工智能`

> Astute RAG: Overcoming Imperfect Retrieval Augmentation and Knowledge Conflicts for Large Language Models

# 摘要

> RAG 虽然能有效整合外部知识以弥补 LLM 的不足，但不完美的检索可能引入不相关、误导甚至恶意信息，从而削弱其效果。尽管重要，先前研究很少深入探讨不完美检索的错误如何影响 RAG，以及 LLM 内部知识与外部来源间的潜在冲突。我们发现，在现实条件下，不完美的检索增强难以避免且危害甚大。我们识别出检索后阶段需克服的瓶颈：LLM 内部与外部知识间的冲突。为增强 LLM 对不完美检索的抵抗力，我们提出 Astute RAG，一种自适应引出 LLM 内部关键信息、迭代整合内外知识并最终根据信息可靠性确定答案的新方法。实验表明，Astute RAG 显著优于现有增强鲁棒性的 RAG 方法，尤其在最坏情况下，其性能甚至超越无 RAG 的 LLM。进一步分析证实，Astute RAG 有效化解知识冲突，大幅提升 RAG 系统的可靠性与可信度。

> Retrieval-Augmented Generation (RAG), while effective in integrating external knowledge to address the limitations of large language models (LLMs), can be undermined by imperfect retrieval, which may introduce irrelevant, misleading, or even malicious information. Despite its importance, previous studies have rarely explored the behavior of RAG through joint analysis on how errors from imperfect retrieval attribute and propagate, and how potential conflicts arise between the LLMs' internal knowledge and external sources. We find that imperfect retrieval augmentation might be inevitable and quite harmful, through controlled analysis under realistic conditions. We identify the knowledge conflicts between LLM-internal and external knowledge from retrieval as a bottleneck to overcome in the post-retrieval stage of RAG. To render LLMs resilient to imperfect retrieval, we propose Astute RAG, a novel RAG approach that adaptively elicits essential information from LLMs' internal knowledge, iteratively consolidates internal and external knowledge with source-awareness, and finalizes the answer according to information reliability. Our experiments using Gemini and Claude demonstrate that Astute RAG significantly outperforms previous robustness-enhanced RAG methods. Notably, Astute RAG is the only approach that matches or exceeds the performance of LLMs without RAG under worst-case scenarios. Further analysis reveals that Astute RAG effectively resolves knowledge conflicts, improving the reliability and trustworthiness of RAG systems.

[Arxiv](https://arxiv.org/abs/2410.07176)