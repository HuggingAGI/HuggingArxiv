# 零-shot 上下文学习中的演示增强策略
发布时间：2024年06月03日

`提示工程`
> Demonstration Augmentation for Zero-shot In-context Learning
>
> 大型语言模型（LLMs）通过情境学习（ICL）展现出惊人的自学能力，无需更新参数即可从文本示例中汲取知识。然而，研究表明，模型性能对示例选择极为敏感，这在实际应用中，尤其是对用户查询缺乏先验知识时，构成了一大挑战。为此，我们不得不建立庞大的示例库并整合外部数据库，这无疑增加了时间和经济成本。鉴于此，近期研究开始关注零-shot ICL，旨在通过发挥模型的内在生成能力，减少对外部信息的依赖。尽管这些方法行之有效，但模型生成的内容可能并不可靠，且生成过程耗时。为此，我们提出了情境学习演示增强（DAIL），利用模型先前的预测结果作为后续学习的示例。DAIL无需额外推理成本，也不依赖模型的生成能力。实验结果显示，DAIL能显著提升模型在零-shot推理上的表现，甚至在无外部信息辅助下超越了少量样本的情境学习。
>
> https://arxiv.org/abs/2406.01224

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01224/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01224/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01224/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01224/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01224/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01224/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01224/x7.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.01224](https://arxiv.org/abs/2406.01224)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886