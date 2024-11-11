# Interaction2Code：我们距离自动交互式网页生成还有多远？
发布时间：2024年11月05日

`代码编写`
> Interaction2Code: How Far Are We From Automatic Interactive Webpage Generation?
>
> 将网页设计转换为功能性的用户界面（UI）代码是构建网站的关键步骤，这可能是劳动密集型和耗时的。为了使这个设计到代码的转换过程自动化，已经提出了使用基于学习的网络和多模态大型语言模型（MLLMs）的各种自动化方法。然而，这些研究仅仅在狭窄范围的静态网页上进行了评估，并忽略了动态交互元素，使得它们在现实世界的网站部署中不太实用。

为了填补空白，我们对 MLLMs 在生成交互式网页方面进行了首次系统研究。具体来说，我们首先制定了交互到代码任务，并构建了包含 97 个独特网页和 213 种不同交互的 Interaction2Code 基准，涵盖 15 种网页类型和 30 个交互类别。然后，我们使用自动指标和人工评估对三个最先进的（SOTA）MLLMs 进行了全面实验，从而相应地总结了六个发现。我们的实验结果突出了 MLLMs 在生成细粒度交互特征以及处理具有复杂变换和微妙视觉修改的交互方面的局限性。我们进一步分析了失败案例及其根本原因，确定了 10 种常见的失败类型并评估了它们的严重程度。此外，我们的发现揭示了三个关键的影响因素，即提示、视觉显著性和文本描述，它们可以提高 MLLMs 的交互生成性能。基于这些发现，我们为研究人员和开发人员得出了启示，为该领域的未来发展提供了基础。数据集和源代码可在 https://github.com/WebPAI/Interaction2Code 获得。
>
> https://arxiv.org/abs/2411.03292

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.03292](https://arxiv.org/abs/2411.03292)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)