# 通过检索助力生成，提升代码注释的质量
发布时间：2024年08月07日

`RAG`
> Improving Retrieval-Augmented Code Comment Generation by Retrieving for Generation
>
> 代码注释生成旨在自动从源代码中提取高质量注释，这一领域已有多年的研究。最新研究通过结合信息检索技术和神经生成模型，提出了检索增强的注释生成（RACG）方法，并取得了显著成果。然而，以往的检索器与生成器是独立构建的，这导致检索到的示例不一定最有利于注释生成，限制了方法的性能。为此，我们提出了一种新的训练策略，使检索器能够从生成器的反馈中学习，从而检索出更有助于提升注释质量的示例。具体而言，在训练中，我们通过检索器获取前k个示例并计算其检索分数，同时利用生成器计算基于这些示例的生成损失。通过将高检索分数的示例与低生成损失的示例对齐，检索器能够学会选择最优示例。基于此策略，我们开发了名为JOINTCOM的新RACG方法，并在两个真实数据集上进行了测试。实验结果显示，JOINTCOM在多个指标上显著超越了现有最先进方法。此外，人工评估也证实了JOINTCOM生成的注释在自然性、信息量和实用性方面均优于其他方法。
>
> https://arxiv.org/abs/2408.03623

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.03623](https://arxiv.org/abs/2408.03623)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)