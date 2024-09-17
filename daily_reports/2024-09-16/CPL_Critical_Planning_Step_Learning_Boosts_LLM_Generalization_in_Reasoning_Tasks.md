# CPL：通过关键规划步骤学习，LLM 在推理任务中的泛化能力得到显著提升。
发布时间：2024年09月13日


> CPL: Critical Planning Step Learning Boosts LLM Generalization in Reasoning Tasks
>
> 训练大型语言模型 (LLM) 以提升推理能力，已在数学推理和代码生成等多个领域取得显著成效。然而，现有方法多聚焦于特定任务的推理优化，而忽视了模型在更广泛推理任务中的泛化能力。为此，我们创新性地提出了关键规划步骤学习 (CPL)，借助蒙特卡洛树搜索 (MCTS) 在多步骤推理任务中探索多样化的规划策略。CPL 通过学习步骤级别的规划偏好，有效提升模型的长期规划能力，进而增强其整体推理能力。此外，尽管直接偏好优化 (DPO) 在许多场景中表现出色，但在处理复杂的多步骤推理任务时，其细粒度监督的不足成为瓶颈。为此，我们进一步提出了步骤级别优势偏好优化 (Step-APO)，将 MCTS 的优势估计融入 DPO，使模型更精准地学习关键的中间规划步骤，从而大幅提升其在推理任务中的泛化能力。实验结果显示，我们的方法在 GSM8K 和 MATH 上的训练，不仅显著提升了这两项任务的性能 (+10.5% 和 +6.5%)，还在 ARC-C、BBH、MMLU-STEM 和 MMLU 等域外推理基准上取得了显著进步 (+4.0%、+1.8%、+2.2% 和 +0.9%)。
>
> https://arxiv.org/abs/2409.08642

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.08642](https://arxiv.org/abs/2409.08642)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)