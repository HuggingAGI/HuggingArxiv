# LLM-R：一个结合分层代理和 RAG 用于生成领域自适应维护方案的框架
发布时间：2024年11月07日

`RAG`
> LLM-R: A Framework for Domain-Adaptive Maintenance Scheme Generation Combining Hierarchical Agents and RAG
>
> 智能设备的使用日益增多，这突显了维护在生产活动中的关键作用。交互式电子技术手册（IETMs）是支持智能设备维护的重要工具。然而，传统的 IETMs 面临着诸如从图形用户界面（GUIs）向自然语言用户界面（LUIs）过渡以及管理复杂逻辑关系等挑战。此外，它们必须满足当前对更高智能的需求。本文提出了一种基于大型语言模型（LLM-R）的维护方案生成方法。所提出的方法包括几个关键创新：我们提出了低秩适应 - 知识保留（LORA-KR）损失技术，以按比例调整混合维护数据，用于微调 LLM。这种方法防止了混合数据引起的知识冲突，提高了模型在特定维护领域的适应性和推理能力。此外，采用了基于分层任务的代理和指令级检索增强生成（RAG）技术来优化生成步骤，并减轻由于模型无法访问上下文信息而导致的幻觉现象。这种增强提高了模型在处理已知或未知维护对象和维护方案场景时的灵活性和准确性。为了验证所提出方法在维护任务中的有效性，使用来自不同领域的对象构建了一个维护方案数据集。实验结果表明，所提出方法生成的维护方案的准确率达到 91.59%，这表明这种改进提高了维护方案的智能性，并为设备维护引入了新的技术方法。
>
> https://arxiv.org/abs/2411.04476

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.04476](https://arxiv.org/abs/2411.04476)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)