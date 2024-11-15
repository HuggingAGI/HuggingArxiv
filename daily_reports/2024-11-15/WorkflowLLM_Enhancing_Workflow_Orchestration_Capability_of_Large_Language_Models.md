# WorkflowLLM：增强大型语言模型的工作流编排能力
发布时间：2024年11月08日

`Agent应用`
> WorkflowLLM: Enhancing Workflow Orchestration Capability of Large Language Models
>
> 大型语言模型（LLM）的最新进展通过基于 LLM 自动化工作流编排流程，推动了流程自动化从机器人流程自动化到智能体流程自动化的革命性范式转变。然而，现有的 LLM（甚至先进的 OpenAI GPT-4o）在工作流编排方面的能力仍不尽人意。为了解决这一限制，我们提出了 WorkflowLLM，这是一个以数据为中心精心设计的框架，旨在增强 LLM 在工作流编排方面的能力。它首先构建了一个包含 106,763 个样本的大规模微调数据集 WorkflowBench，涵盖了来自 28 个类别的 83 个应用程序的 1,503 个 API。具体来说，构建过程可分为三个阶段：（1）数据收集：我们从 Apple Shortcuts 和 RoutineHub 收集真实世界的工作流数据，将其转录为 Python 风格的代码。我们还通过 ChatGPT 为其配备生成的分层思维。（2）查询扩展：我们提示 ChatGPT 生成更多任务查询，以丰富工作流的多样性和复杂性。（3）工作流生成：我们利用在收集数据上训练的注释器模型为合成查询生成工作流。最后，我们将通过质量确认的合成样本与收集的样本合并，以获得 WorkflowBench。基于 WorkflowBench，我们对 Llama-3.1-8B 进行微调以获得 WorkflowLlama。我们的实验表明，WorkflowLlama 展示出了编排复杂工作流的强大能力，同时在以前未见过的 API 上也实现了显著的泛化性能。此外，WorkflowBench 在分布外任务规划数据集 T-Eval 上表现出强大的零样本泛化能力。我们的数据和代码可在 https://github.com/OpenBMB/WorkflowLLM 上获取。
>
> https://arxiv.org/abs/2411.05451

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.05451](https://arxiv.org/abs/2411.05451)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)