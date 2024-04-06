# 利用大型语言模型挖掘潜在关系，优化序列推荐策略。
`推荐系统`
> 序列推荐系统通过分析用户过往的互动历史来预测他们可能感兴趣的商品。传统方法主要捕捉商品间的隐式协同过滤信号。而新兴的关联感知模型通过明确整合商品关系，已在用户历史序列建模中展现出优异表现，尽管这些关系大多来源于知识图谱。然而，现有方法过度依赖预设的关系，受限于稀疏性问题，影响了在多样化商品关系场景下的泛化能力。本文提出了一个创新的关联感知推荐框架——潜在关系发现（LRD）。区别于以往依赖固定规则的模型，我们创新性地运用大型语言模型（LLM）来探索商品间新的关系和联系。这一灵感源自人类使用自然语言描述商品关系的天赋，LRD借鉴了LLM类似人类的知识理解能力，获取商品的语言知识表示。这些表示随后被送入基于离散状态变分自编码器（DVAE）的潜在关系发现模块。接着，我们对关系发现任务和推荐任务进行联合优化。多个公共数据集的实验结果显示，我们提出的潜在关系发现方法能显著提升现有关联感知推荐模型的性能。更深入的分析实验验证了这些发现的潜在关系的有效性和可靠性。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18348/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18348/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18348/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18348/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18348/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2403.18348/x6.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/2855811855858241](https://wx.zsxq.com/dweb2/index/topic_detail/2855811855858241)

[https://arxiv.org/abs/2403.18348](https://arxiv.org/abs/2403.18348)