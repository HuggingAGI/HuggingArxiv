# GRAG：图检索赋能生成
发布时间：2024年05月26日

`RAG`
> GRAG: Graph Retrieval-Augmented Generation
>
> 检索增强生成（RAG）虽提升了生成语言模型的响应准确性和相关性，但在文本与拓扑信息并重的图环境中表现欠佳。传统的RAG方法忽视了文本图的结构复杂性，导致生成过程中的关键缺陷。为此，我们提出了图检索增强生成（GRAG），通过强调子图结构的重要性，大幅提升了检索与生成的效果。与仅关注文本实体检索的RAG不同，GRAG对图的拓扑结构保持高度敏感，这对于生成既符合上下文又事实准确的响应至关重要。GRAG方法分为四个阶段：$k$-跳自我图索引、图检索、软修剪以减少无关实体影响，以及利用修剪后的文本子图进行生成。其核心流程——先检索后软修剪文本子图——有效识别相关子图，避免了NP难问题的计算负担。我们还创新了一种提示策略，实现文本子图到分层文本描述的无损转换。在多跳推理图基准的广泛测试中，GRAG在需要文本图多跳推理的场景下，不仅显著超越现有RAG技术，还大幅减少了幻觉现象。
>
> https://arxiv.org/abs/2405.16506

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16506/intro_3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16506/flow_4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16506/subgraph.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16506/webqsp.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.16506](https://arxiv.org/abs/2405.16506)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886