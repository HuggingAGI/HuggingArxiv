# CriSPO：一种多角度批评与建议引导的文本生成自动提示优化工具
发布时间：2024年10月03日

`提示工程`
> CriSPO: Multi-Aspect Critique-Suggestion-guided Automatic Prompt Optimization for Text Generation
>
> 大型语言模型 (LLM) 通过提示技术能够跨领域生成流畅的摘要，从而减少了对专门训练摘要模型的需求。然而，如何设计有效的提示，使 LLM 生成既详细又符合风格的摘要，仍是一个难题。本文探讨了利用源文档中的显著信息来优化摘要提示的方法。实验表明，在提示中加入关键词能显著提升 ROUGE F1 和召回率，使生成的摘要更接近参考标准且更完整。关键词的数量还能调节精确度与召回率之间的平衡。此外，研究发现，整合短语级别的显著信息比单词或句子级别更为有效。不过，这种优化对幻觉现象的影响在不同 LLM 中表现不一。为此，我们开发了关键词信号提取器 (CriSPO)，一个轻量级模型，可微调以提取显著关键词。使用 CriSPO，我们实现了在各类数据集和开源及专有 LLM 上的一致 ROUGE 提升，且无需对 LLM 进行定制。这些发现为构建基于提示的摘要系统提供了宝贵的见解。
>
> https://arxiv.org/abs/2410.02748

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.02748](https://arxiv.org/abs/2410.02748)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)