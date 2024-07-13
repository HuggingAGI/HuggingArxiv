# 极弱监督下的开放世界多标签文本分类
发布时间：2024年07月08日

`文本分类`
> Open-world Multi-label Text Classification with Extremely Weak Supervision
>
> 在极弱监督下，我们探索了开放世界的多标签文本分类，用户仅提供简要描述而无需任何标签。我们发现多数文档有一个主导类，而长尾标签偶尔也会成为主导。基于此，我们利用用户描述引导大型语言模型提取关键词，通过聚类构建标签空间，并运用零-shot分类器精确定位文档，以发现更多长尾标签。这一迭代过程最终形成了X-MLClass方法，显著提升了标签空间覆盖率，如在AAPD数据集上提升了40%，并实现了顶尖的多标签分类准确性。
>
> https://arxiv.org/abs/2407.05609

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.05609/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.05609/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.05609/x3.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.05609](https://arxiv.org/abs/2407.05609)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1