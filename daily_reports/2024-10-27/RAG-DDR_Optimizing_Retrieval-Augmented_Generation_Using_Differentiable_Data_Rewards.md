# RAG-DDR：通过可微数据奖励优化检索增强生成
发布时间：2024年10月17日

`RAG`
> RAG-DDR: Optimizing Retrieval-Augmented Generation Using Differentiable Data Rewards
>
> RAG 通过从外部资源检索知识，有效减少了 LLM 中的幻觉。为使 LLM 适应 RAG 流程，现有方法通过指令调优优化 LLM，提升其利用检索知识的能力。然而，这种监督微调方法使 RAG 模块过度拟合训练信号，忽略了 RAG 系统中不同代理的数据偏好差异。本文提出可微分数据奖励 (DDR) 方法，通过调整 RAG 模块间的数据偏好，端到端训练 RAG 系统。DDR 通过回滚方法收集奖励，优化每个代理，提示代理采样潜在响应作为扰动，评估其对 RAG 系统的影响，并优化代理以提升系统性能。实验表明，DDR 显著优于 SFT 方法，尤其适用于依赖检索知识的小规模参数 LLM。此外，DDR 能更有效地调整 RAG 模块间的数据偏好，使生成模块在提取关键信息和减少参数记忆与外部知识冲突方面更有效。所有代码可在 https://github.com/OpenMatch/RAG-DDR 获取。
>
> https://arxiv.org/abs/2410.13509

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.13509](https://arxiv.org/abs/2410.13509)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)