# 借助大型语言模型来合成产品合意性的数据集

发布时间：2024年11月20日

`LLM应用` `产品评估` `语言模型`

> Utilizing Large Language Models to Synthesize Product Desirability Datasets

# 摘要

> 本研究探索了大型语言模型（LLMs）在为产品合意性工具包（PDT）测试生成合成数据集方面的运用，这是评估用户情感和产品体验的关键一环。借助 gpt-4o-mini 这一相比大型商业 LLMs 更具性价比的选择，分别采用了 Word+Review、Review+Word 和 Supply-Word 这三种方法，每种方法均合成了 1000 条产品评论。针对生成的数据集，从情绪一致性、文本多样性和数据生成成本等方面进行了评估。结果显示，所有方法的情绪一致性都很高，皮尔逊相关系数在 0.93 至 0.97 之间。Supply-Word 展现出了最高的多样性和对 PDT 术语的覆盖度，不过生成成本有所提高。尽管存在轻微偏向积极情绪的情况，但在测试数据有限时，LLM 生成的合成数据优势显著，涵盖可扩展性、成本节省以及数据集生成的灵活性。

> This research explores the application of large language models (LLMs) to generate synthetic datasets for Product Desirability Toolkit (PDT) testing, a key component in evaluating user sentiment and product experience. Utilizing gpt-4o-mini, a cost-effective alternative to larger commercial LLMs, three methods, Word+Review, Review+Word, and Supply-Word, were each used to synthesize 1000 product reviews. The generated datasets were assessed for sentiment alignment, textual diversity, and data generation cost. Results demonstrated high sentiment alignment across all methods, with Pearson correlations ranging from 0.93 to 0.97. Supply-Word exhibited the highest diversity and coverage of PDT terms, although with increased generation costs. Despite minor biases toward positive sentiments, in situations with limited test data, LLM-generated synthetic data offers significant advantages, including scalability, cost savings, and flexibility in dataset production.

[Arxiv](https://arxiv.org/abs/2411.13485)