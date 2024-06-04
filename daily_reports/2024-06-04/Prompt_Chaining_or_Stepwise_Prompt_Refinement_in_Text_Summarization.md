# 是采用提示链还是逐步提示？探讨文本摘要中的细化策略
发布时间：2024年06月01日

`提示工程`
> Prompt Chaining or Stepwise Prompt? Refinement in Text Summarization
>
> 大型语言模型（LLMs）通过模仿人类从初稿开始的批评与迭代改进过程，有效提升了摘要质量。为此，研究者设计了两种迭代策略：提示链（Prompt Chaining）和逐步提示（Stepwise Prompt）。前者通过三个独立提示串联起草、批评与改进阶段，后者则将这些阶段融于单一提示之中。尽管如此，两种方法的优劣尚未得到充分探讨。本文旨在对比这两种方法在文本摘要中的表现，以揭示最佳策略。实验表明，提示链方法效果更佳，可能因其模拟的改进过程更贴近实际。鉴于改进过程的通用性，我们的发现有望应用于其他领域，为LLMs的广泛发展提供新思路。
>
> https://arxiv.org/abs/2406.00507

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00507/x1.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.00507](https://arxiv.org/abs/2406.00507)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886