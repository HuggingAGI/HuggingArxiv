# 基于 LLM 的弱监督框架，助力视频搜索中的查询意图精准分类

发布时间：2024年09月13日

`LLM应用` `流媒体` `人工智能`

> LLM-based Weak Supervision Framework for Query Intent Classification in Video Search

# 摘要

> 流媒体服务改变了我们与数字娱乐互动的方式。尽管技术进步，理解用户多样化的搜索查询仍是一大挑战。一个能处理各种用户意图的查询理解系统至关重要。我们可以通过训练NLU模型来构建此系统，但获取高质量的标记数据却是一大难题。手动注释成本高且难以捕捉用户词汇的多样性。为此，我们提出了一种新方法，利用LLM通过弱监督自动注释大量用户查询。通过提示工程和多样化的LLM角色，我们生成的训练数据符合人类注释者的期望。结合领域知识，我们的方法训练出低延迟模型，优化实时推理。评估显示，我们的方法在召回率上平均提升了113%，优于基线。此外，我们的提示工程框架提高了LLM生成数据的质量，LLM预测与人类注释的一致率提高了47.60%。角色选择路由机制进一步提升了3.67%的加权F1分数。

> Streaming services have reshaped how we discover and engage with digital entertainment. Despite these advancements, effectively understanding the wide spectrum of user search queries continues to pose a significant challenge. An accurate query understanding system that can handle a variety of entities that represent different user intents is essential for delivering an enhanced user experience. We can build such a system by training a natural language understanding (NLU) model; however, obtaining high-quality labeled training data in this specialized domain is a substantial obstacle. Manual annotation is costly and impractical for capturing users' vast vocabulary variations. To address this, we introduce a novel approach that leverages large language models (LLMs) through weak supervision to automatically annotate a vast collection of user search queries. Using prompt engineering and a diverse set of LLM personas, we generate training data that matches human annotator expectations. By incorporating domain knowledge via Chain of Thought and In-Context Learning, our approach leverages the labeled data to train low-latency models optimized for real-time inference. Extensive evaluations demonstrated that our approach outperformed the baseline with an average relative gain of 113% in recall. Furthermore, our novel prompt engineering framework yields higher quality LLM-generated data to be used for weak supervision; we observed 47.60% improvement over baseline in agreement rate between LLM predictions and human annotations with respect to F1 score, weighted according to the distribution of occurrences of the search queries. Our persona selection routing mechanism further adds an additional 3.67% increase in weighted F1 score on top of our novel prompt engineering framework.

[Arxiv](https://arxiv.org/abs/2409.08931)