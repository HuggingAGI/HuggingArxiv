# 思维图谱探析
发布时间：2024年09月16日


> On the Diagram of Thought
>
> 我们推出了思维图（DoT），一个将大型语言模型（LLM）中的迭代推理建模为单个模型内有向无环图（DAG）构建的框架。与传统方法不同，DoT将命题、批评、改进和验证组织成连贯的DAG结构，使模型在保持逻辑一致性的同时探索复杂推理路径。每个节点对应一个已被提出、批评、改进或验证的命题，使LLM通过自然语言反馈迭代改进推理。通过角色特定标记的自回归下一标记预测，DoT促进提出想法和批判性评估之间的无缝过渡，提供更丰富的反馈。我们还使用拓扑理论正式化了DoT框架，确保推理过程中的逻辑一致性和健全性。这种方法增强了单个LLM的训练和推理过程，无需多个模型或外部控制机制。DoT为设计下一代推理专用模型提供了概念框架，强调训练效率、强大推理能力和理论基础。代码可在https://github.com/diagram-of-thought/diagram-of-thought获取。
>
> https://arxiv.org/abs/2409.10038

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.10038](https://arxiv.org/abs/2409.10038)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)