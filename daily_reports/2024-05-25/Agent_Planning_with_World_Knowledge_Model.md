# 基于世界知识模型的智能代理规划
发布时间：2024年05月23日

`Agent应用`
> Agent Planning with World Knowledge Model
>
> 近期，大型语言模型（LLMs）作为代理模型在执行交互式规划任务方面取得了显著进展，但仍受限于对真实物理世界理解的不足，导致全球规划中盲目试错和局部规划中产生幻觉行动。为此，本文提出了参数化世界知识模型（WKM），模仿人类心理模型，预先提供全局知识，并在任务中动态更新局部知识，以优化代理规划。我们训练代理模型从专家和采样数据中自主学习，并利用WKM为全局和局部规划提供知识支持。实验证明，我们的方法在多个复杂数据集上超越了现有技术，有效减少了试错和幻觉行动，增强了代理对世界的理解。此外，我们还发现：1）我们的任务知识能有效泛化至新任务；2）即使较弱的WKM也能指导强大的代理模型；3）统一的WKM训练展现出广阔的发展前景。相关代码将公开于https://github.com/zjunlp/WKM。
>
> https://arxiv.org/abs/2405.14205


<hr />

- 论文原文: [https://arxiv.org/abs/2405.14205](https://arxiv.org/abs/2405.14205)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886