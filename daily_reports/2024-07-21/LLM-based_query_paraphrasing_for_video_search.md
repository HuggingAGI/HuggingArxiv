# 利用 LLM 进行视频搜索查询的改写
发布时间：2024年07月17日

`多模态大模型`
> LLM-based query paraphrasing for video search
>
> 文本到视频检索通过概念和嵌入搜索来回应用户查询，但由于概念库和训练数据的限制，常因词汇外问题导致效果不佳。此外，现有搜索方法无法处理包含逻辑和空间约束的复杂查询。为此，我们采用大型语言模型（LLM）通过文本到文本（T2T）、文本到图像（T2I）和图像到文本（I2T）转换来简化查询，有效应对词汇外问题，并将复杂查询分解为简单子查询，提升检索性能。针对LLM可能产生的错误，我们提出了一种基于一致性的验证策略，确保改述查询的准确性。在TRECVid数据集上进行的实验显示，通过查询改述，传统难以回答的查询得到了有效解决。
>
> https://arxiv.org/abs/2407.12341


<hr />

- 论文原文: [https://arxiv.org/abs/2407.12341](https://arxiv.org/abs/2407.12341)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1