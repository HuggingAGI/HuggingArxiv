# 捕捉研究文献对可持续发展目标的态度：一种基于大型语言模型的主题建模方法

发布时间：2024年11月05日

`LLM应用` `可持续发展`

> Capturing research literature attitude towards Sustainable Development Goals: an LLM-based topic modeling approach

# 摘要

> 世界正面临着众多阻碍人类文明发展和地球上人类福祉的挑战。联合国于 2015 年制定了可持续发展目标（SDG），以在 2030 年前应对这些全球挑战。自然语言处理技术可以帮助揭示研究文献中关于可持续发展目标的讨论。我们提出了一个完全自动化的流程：1）从 Scopus 数据库获取内容，并准备专门针对五组可持续发展目标的数据集；2）进行主题建模，这是一种用于在大量文本数据集合中识别主题的统计技术；3）通过基于关键词的搜索和主题频率时间序列提取实现主题探索。对于主题建模，我们利用扩展的 BERTopic 堆栈应用于大型文本文档语料库（我们在数十万份文档中发现了数百个主题），引入了 i）一种基于新型 LLM 的嵌入计算，用于在连续空间中表示科学摘要，以及 ii）一个超参数优化器，以有效地为任何新的大型数据集找到最佳配置。我们还在交互式仪表板上生成结果的可视化，报告主题的时间演变。结果可检查和可探索，有助于主题建模过程的可解释性。我们提出的基于 LLM 的大型文本数据集主题建模流程允许用户捕捉 2006 - 2023 年期间科学摘要中对可持续发展目标态度的演变见解。使用我们的系统，所有结果均可重现；该工作流程可以推广到在任何时间点应用于任何大型文本文档语料库。

> The world is facing a multitude of challenges that hinder the development of human civilization and the well-being of humanity on the planet. The Sustainable Development Goals (SDGs) were formulated by the United Nations in 2015 to address these global challenges by 2030. Natural language processing techniques can help uncover discussions on SDGs within research literature. We propose a completely automated pipeline to 1) fetch content from the Scopus database and prepare datasets dedicated to five groups of SDGs; 2) perform topic modeling, a statistical technique used to identify topics in large collections of textual data; and 3) enable topic exploration through keywords-based search and topic frequency time series extraction. For topic modeling, we leverage the stack of BERTopic scaled up to be applied on large corpora of textual documents (we find hundreds of topics on hundreds of thousands of documents), introducing i) a novel LLM-based embeddings computation for representing scientific abstracts in the continuous space and ii) a hyperparameter optimizer to efficiently find the best configuration for any new big datasets. We additionally produce the visualization of results on interactive dashboards reporting topics' temporal evolution. Results are made inspectable and explorable, contributing to the interpretability of the topic modeling process. Our proposed LLM-based topic modeling pipeline for big-text datasets allows users to capture insights on the evolution of the attitude toward SDGs within scientific abstracts in the 2006-2023 time span. All the results are reproducible by using our system; the workflow can be generalized to be applied at any point in time to any big corpus of textual documents.

[Arxiv](https://arxiv.org/abs/2411.02943)