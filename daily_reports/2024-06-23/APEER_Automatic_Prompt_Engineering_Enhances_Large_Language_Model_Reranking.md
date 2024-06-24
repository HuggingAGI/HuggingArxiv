# APEER：自动提示工程技术，显著提升了大型语言模型在文本重排序任务中的性能。
发布时间：2024年06月20日

`提示工程`
> APEER: Automatic Prompt Engineering Enhances Large Language Model Reranking
>
> 大型语言模型（LLMs）极大地提升了信息检索（IR）中各模块的性能，尤其是在重排序方面。尽管成绩斐然，但目前的零-shot相关性排序仍严重依赖人工设计的提示。现有的自动提示工程算法多聚焦于语言建模和分类任务，对IR领域，尤其是重排序的研究尚显不足。由于输入中查询与长文本对的复杂结合，排序任务的难度远超分类，直接应用现有提示工程算法面临挑战。为此，我们推出了一种名为APEER的新型自动提示工程算法，旨在减少人工干预，并挖掘重排序中提示优化的潜力。APEER通过迭代反馈和偏好优化，不断精炼提示。在四个LLMs和十个数据集上的广泛测试显示，APEER显著超越了当前最先进的手动提示方法。更有甚者，APEER生成的提示在跨任务和跨LLMs的应用中展现出更佳的迁移能力。相关代码已公开于https://github.com/jincan333/APEER。
>
> https://arxiv.org/abs/2406.14449

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14449/performance.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14449/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14449/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14449/x3.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.14449](https://arxiv.org/abs/2406.14449)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2