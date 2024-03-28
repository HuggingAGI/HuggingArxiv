# MeTMaP是一种应用于LLM增强生成场景的变形测试技术，旨在有效发现并解决其中的虚假向量匹配问题。

发布时间：2024年02月22日

`LLM应用`

> MeTMaP: Metamorphic Testing for Detecting False Vector Matching Problems in LLM Augmented Generation

# 摘要

> 诸如RAG和CAG之类的增强生成技术通过融合外部知识和缓存信息，有力地推动了大型语言模型(LLM)性能的进步。然而，在确保向量数据库准确匹配这一关键环节上，尤其是在应用于自然语言处理任务时，尚面临巨大挑战。一旦向量数据库发生误匹配，将极大地削弱LLM输出的准确性和可靠性，甚至引发误导或错误反馈。针对此类重要问题，目前尚缺乏有效的检测与解决方案。本文介绍了一项名为MeTMaP的变形测试框架，它专门设计用于发现LLM增强生成系统中的错误向量匹配现象。我们基于“语义相似文本应当匹配，反之则不应匹配”的原则，从六个NLP数据集中提炼出了8种核心变形关系(MRs)。MeTMaP运用这些MRs构建测试用的句子三元组，模拟真实的LLM应用场景。经过在包含29种嵌入模型和7种距离度量方式的203种向量匹配配置上的深入评估，MeTMaP揭示了显著的不准确性问题。测试结果显示，相较于原始数据集，MeTMaP在我们的测试中最高准确率仅达到41.51%，这进一步强调了在向量匹配方法中错误匹配问题的广泛存在，同时也凸显了在LLM增强应用中亟需研发有效检测和应对措施的重要性。

> Augmented generation techniques such as Retrieval-Augmented Generation (RAG) and Cache-Augmented Generation (CAG) have revolutionized the field by enhancing large language model (LLM) outputs with external knowledge and cached information. However, the integration of vector databases, which serve as a backbone for these augmentations, introduces critical challenges, particularly in ensuring accurate vector matching. False vector matching in these databases can significantly compromise the integrity and reliability of LLM outputs, leading to misinformation or erroneous responses. Despite the crucial impact of these issues, there is a notable research gap in methods to effectively detect and address false vector matches in LLM-augmented generation. This paper presents MeTMaP, a metamorphic testing framework developed to identify false vector matching in LLM-augmented generation systems. We derive eight metamorphic relations (MRs) from six NLP datasets, which form our method's core, based on the idea that semantically similar texts should match and dissimilar ones should not. MeTMaP uses these MRs to create sentence triplets for testing, simulating real-world LLM scenarios. Our evaluation of MeTMaP over 203 vector matching configurations, involving 29 embedding models and 7 distance metrics, uncovers significant inaccuracies. The results, showing a maximum accuracy of only 41.51\% on our tests compared to the original datasets, emphasize the widespread issue of false matches in vector matching methods and the critical need for effective detection and mitigation in LLM-augmented applications.

[Arxiv](https://arxiv.org/abs/2402.14480)