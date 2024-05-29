# RAGSys：将物品冷启动推荐系统化身为RAG系统
发布时间：2024年05月27日

`RAG`
> RAGSys: Item-Cold-Start Recommender as RAG System
>
> 大型语言模型（LLM）虽潜力巨大，但通用知识常难满足特定领域需求。微调虽常用，却易导致灾难性遗忘和泛化障碍。情境学习（ICL）另辟蹊径，借助检索增强生成（RAG）为LLM提供少量学习任务的相关演示。本文深入探讨了ICL中演示检索系统的理想特质，并指出其与项目冷启动推荐系统相似，更注重发现与信息增益而非严格相关性。我们创新性地提出了一种评估方法，通过LLM在NLP任务上的表现来衡量，摒弃了主观多样性评分。研究揭示，演示检索中的多样性与质量偏差对ICL效果至关重要，并凸显了推荐系统技术在此领域的应用前景。
>
> https://arxiv.org/abs/2405.17587

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17587/cosine_sim_vs_dpo.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.17587](https://arxiv.org/abs/2405.17587)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886