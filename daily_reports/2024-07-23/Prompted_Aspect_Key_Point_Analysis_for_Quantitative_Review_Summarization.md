# 通过提示关键点分析，实现评论的定量摘要
发布时间：2024年07月19日


> Prompted Aspect Key Point Analysis for Quantitative Review Summarization
>
> 关键点分析 (KPA) 旨在提供简洁的文本摘要和衡量其普遍性的数量。大多数针对评论的 KPA 研究采用监督学习提取短句作为关键点 (KP)，然后匹配评论以量化 KP 的普遍性。然而，最近的抽象方法常导致 KP 包含重叠和幻觉观点，量化不准确。为此，我们提出提示方面关键点分析 (PAKPA)，利用方面情感分析和大型语言模型 (LLM) 的提示上下文学习，生成和量化基于方面的 KP，实现忠实且准确的量化，并减少对大量标注数据的依赖。实验表明，我们的框架在 Yelp 和 SPACE 数据集上达到了最先进的性能。源代码和数据可在此获取：https://github.com/antangrocket1312/PAKPA
>
> https://arxiv.org/abs/2407.14049

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14049/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14049/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14049/x3.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.14049](https://arxiv.org/abs/2407.14049)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1