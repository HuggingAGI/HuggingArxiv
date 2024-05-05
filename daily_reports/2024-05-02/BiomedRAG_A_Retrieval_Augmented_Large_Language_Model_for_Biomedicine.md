![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# BiomedRAG：一种为生物医学领域设计的、结合了检索功能的先进大型语言模型。
发布时间：2024年05月01日

`RAG`
> 大型语言模型（LLMs）在生物医学和医疗领域的多样化应用中迅速崭露头角，尽管它们有时会生成错误信息或产生幻觉。为了解决这些问题，检索增强生成技术应运而生，帮助模型刷新知识库并提升性能。与以往的检索增强语言模型相比，这些模型通常使用专门的交叉注意力机制来编码检索到的文本，BiomedRAG则采取了更为简洁的方法，直接将检索到的块状文档输入LLM。这种设计简化了现有检索和语言模型的应用，有效过滤了检索文档中的噪声，尤其是在噪声较多的任务中。此外，我们的研究还展示了利用LLM指导生物医学领域检索模型的潜力，以检索出能够辅助LLM提升预测准确度的文档。实验结果显示，在经过调整的评分器辅助下，BiomedRAG在5项生物医学自然语言处理任务上均展现出色的表现，这些任务包括信息抽取（三元组抽取、关系抽取）、文本分类、链接预测和问答，涵盖了9个以上的数据集。以三元组抽取任务为例，BiomedRAG在GIT和ChemProt语料库上的微F1分数分别达到了81.42和88.83，超越了其他同类系统。



- 论文原文: [https://arxiv.org/abs/2405.00465](https://arxiv.org/abs/2405.00465)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)