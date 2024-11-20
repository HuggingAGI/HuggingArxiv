# 借助大型语言模型实现情感分析中的代码混合数据增强

发布时间：2024年11月01日

`LLM应用` `情感分析`

> Leveraging Large Language Models for Code-Mixed Data Augmentation in Sentiment Analysis

# 摘要

> 代码混合（CM），也就是说话者在单个表述里融合多种语言，在多语言社会中颇为常见，但其复杂性和有限的数据给自然语言处理造成了难题。我们建议运用大型语言模型来生成合成的CM数据，进而用于提升针对CM情感分析的任务专用模型的性能。我们的成果显示，在西班牙语 - 英语中，合成数据让F1分数提升了9.32%，胜过以往的增强技术。然而，在马拉雅拉姆语 - 英语中，只有基线较低时，合成数据才有用；在有强大的自然数据的情况下，额外的合成数据几乎没什么帮助。人工评估证实，此方法是生成听起来自然的CM句子的简便、高性价比的途径，对低基线尤其有利。我们的发现表明，大型语言模型的少样本提示是CM数据增强的一种颇具前景的手段，对改进情感分析影响显著，这是社会影响系统发展中的一个关键要素。

> Code-mixing (CM), where speakers blend languages within a single expression, is prevalent in multilingual societies but poses challenges for natural language processing due to its complexity and limited data. We propose using a large language model to generate synthetic CM data, which is then used to enhance the performance of task-specific models for CM sentiment analysis. Our results show that in Spanish-English, synthetic data improved the F1 score by 9.32%, outperforming previous augmentation techniques. However, in Malayalam-English, synthetic data only helped when the baseline was low; with strong natural data, additional synthetic data offered little benefit. Human evaluation confirmed that this approach is a simple, cost-effective way to generate natural-sounding CM sentences, particularly beneficial for low baselines. Our findings suggest that few-shot prompting of large language models is a promising method for CM data augmentation and has significant impact on improving sentiment analysis, an important element in the development of social influence systems.

[Arxiv](https://arxiv.org/abs/2411.00691)