# KG-CTG：借助知识图谱引导的大型语言模型实现引文自动生成
`知识图谱`
> 在自然语言处理领域，引用文本生成（CTG）致力于在原始文档中准确引用或参考其他文献。这一任务通过结合原始文献与引用文献的上下文信息，确保生成的文本提供恰当的引用资料。传统研究多从文本摘要角度出发进行引用生成。本研究提出了一个新的框架，并通过比较研究展示了大型语言模型（LLMs）在生成引用文本方面的应用。通过在提示中加入论文间的知识图谱关系，我们进一步提升了模型的生成质量，使其更好地理解文献间的关系。为检验模型效能，我们选用了S2ORC数据集的英文计算机科学论文子集进行测试。结果显示，Vicuna在此任务中以14.15的Meteor得分、12.88的Rouge-1、1.52的Rouge-2和10.94的Rouge-L领先。同时，Alpaca模型通过融入知识图谱，将Rouge-1的得分提升了36.98%，Meteor得分提升了33.14%，表现尤为出色。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.09763/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.09763/single_citation_architecture.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.09763/prompt1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.09763/prompt2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.09763/table_1_without.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.09763/table_1_with.jpg)

[https://wx.zsxq.com/dweb2/index/topic_detail/4844584252124588](https://wx.zsxq.com/dweb2/index/topic_detail/4844584252124588)

[https://arxiv.org/abs/2404.09763](https://arxiv.org/abs/2404.09763)