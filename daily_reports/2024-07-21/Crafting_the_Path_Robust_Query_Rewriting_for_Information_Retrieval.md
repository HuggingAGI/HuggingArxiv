# 精雕细琢路径：强化信息检索中的查询重写能力
发布时间：2024年07月17日


> Crafting the Path: Robust Query Rewriting for Information Retrieval
>
> 查询重写的目标是生成一个新查询，以补充原始查询，从而提升信息检索系统的性能。近期研究如Q2D、Q2E和Q2C，依赖于大型语言模型的内部知识来生成相关段落，以丰富查询内容。然而，当所需知识未被模型固有参数包含时，这些方法的效果可能大打折扣。为此，我们提出了一种名为“定制路径”的新型结构化查询重写方法，专为检索系统量身打造。该方法通过三步流程，逐步构建查询相关信息，以精准定位搜索段落。具体步骤包括：查询概念理解、查询类型识别和预期答案提取。实验表明，我们的方法在LLM不太熟悉的领域表现尤为出色，且对模型内部参数的依赖性较低，生成的查询错误更少。此外，与基线方法相比，“定制路径”的延迟更低。
>
> https://arxiv.org/abs/2407.12529

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.12529/x1.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.12529](https://arxiv.org/abs/2407.12529)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1