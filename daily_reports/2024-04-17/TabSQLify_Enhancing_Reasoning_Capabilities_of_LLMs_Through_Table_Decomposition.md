# TabSQLify：通过表格解构，提升大型语言模型的推理技能
发布时间：2024年04月15日
`图表问答`
> 表格推理任务考验着对自然语言和结构化数据的理解能力。尽管大型语言模型（LLMs）在语言理解与生成方面表现卓越，面对庞大的表格数据却因输入限制而力不从心。本文介绍了TabSQLify，一种创新方法，通过文本转SQL技术，将大表格拆解为只含关键信息的小型子表格，以便于回答问题或验证陈述。在对四大挑战性数据集的评估中，该方法与使用完整表格的现有方法相比，表现出不相上下甚至更优的性能。此外，它大幅缩短了输入长度，提高了大规模表格推理应用的可扩展性和效率。在WikiTQ基准测试中，TabSQLify的准确度达到了64.7%，在TabFact基准测试中更是高达79.5%，超越了基于gpt-3.5-turbo（chatgpt）的其他LLM模型。通过显著缩减表格规模，TabSQLify在不牺牲性能的前提下，有效减轻了LLMs处理大型表格时的计算压力。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10150/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10150/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10150/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10150/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10150/reduction2.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/4844588414215218](https://wx.zsxq.com/dweb2/index/topic_detail/4844588414215218)

[https://arxiv.org/abs/2404.10150](https://arxiv.org/abs/2404.10150)