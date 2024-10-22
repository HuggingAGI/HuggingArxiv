# 利用蕴含调优提升密集段落检索效果

发布时间：2024年10月21日

`RAG` `信息检索`

> Improve Dense Passage Retrieval with Entailment Tuning

# 摘要

> 检索模块能提升多种 NLP 任务的性能，如开放域问答和检索增强生成。检索系统的核心在于计算查询与段落间的相关性分数，但相关性定义常模糊。我们发现，相关性主要与 NLI 任务中的蕴含概念相符。基于此，我们设计了“蕴含调优”方法，改进密集检索器的嵌入。通过存在声明作为桥梁，统一检索与 NLI 数据格式，训练检索器预测段落中的蕴含声明。该方法可高效融入现有密集检索技术，实验证明其有效性。

> Retrieval module can be plugged into many downstream NLP tasks to improve their performance, such as open-domain question answering and retrieval-augmented generation. The key to a retrieval system is to calculate relevance scores to query and passage pairs. However, the definition of relevance is often ambiguous. We observed that a major class of relevance aligns with the concept of entailment in NLI tasks. Based on this observation, we designed a method called entailment tuning to improve the embedding of dense retrievers. Specifically, we unify the form of retrieval data and NLI data using existence claim as a bridge. Then, we train retrievers to predict the claims entailed in a passage with a variant task of masked prediction. Our method can be efficiently plugged into current dense retrieval methods, and experiments show the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2410.15801)