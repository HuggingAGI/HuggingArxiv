![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# 本文通过上下文扰动的方法，探讨了在科学问答领域中大型语言模型的弃权行为特征。
发布时间：2024年04月18日

`提示工程`
> 在不确定性面前，模型应选择不回答问题，以防误导用户。本研究探讨了大型语言模型（LLMs）在面对不完整或错误上下文时，能否拒绝回答与上下文相关的科学问题。我们通过多种情境测试了模型的敏感度：去除正确上下文、用无关上下文替代、以及在已有上下文之外增加额外信息。在四个问答（QA）数据集的实验中，我们发现不同模型、不同类型的上下文提供方式，以及问题类型的不同，都会导致性能的显著差异；特别是，许多LLMs在标准问答提示下似乎无法避免回答布尔类型的问题。此外，我们的分析还揭示了放弃回答对问答任务准确度的意外影响。有趣的是，在某些情况下，用无关上下文替换或增加到正确上下文中，可以提升放弃回答的表现，进而提高任务的整体性能。这些发现指出，问答数据集的设计和评估需要改进，以便更有效地评估模型放弃回答的准确性及其对下游任务的影响。



- 论文原文: [https://arxiv.org/abs/2404.12452](https://arxiv.org/abs/2404.12452)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)