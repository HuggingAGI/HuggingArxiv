# 设计一个能够感知、反思并规划的LLM代理，实现无需指令的目标导向城市导航。
发布时间：2024年08月07日

`Agent应用`
> Perceive, Reflect, and Plan: Designing LLM Agent for Goal-Directed City Navigation without Instructions
>
> 本文探讨了城市导航中的一项挑战：AI代理需根据目标位置相对于知名地标的语言描述，仅凭周围环境的观察来导航，无需任何指令。这一任务极具挑战性，因为它要求代理在复杂且地标常不可见的城市环境中，自我定位并构建空间认知。在缺乏导航指引的情况下，这些能力对代理在长距离导航中做出明智决策至关重要。尽管大型语言模型（LLMs）的推理能力为这一问题提供了新的解决思路，但直接应用这些模型作为基线效果不佳，代理常陷入重复访问同一地点和做出短视决策的困境。为此，本文提出了一种结合感知、反思和规划的新型代理工作流程。我们通过微调LLaVA-7B模型，使其能精确感知地标方向与距离，辅助城市导航。同时，通过记忆机制实现反思，整合过往经验与当前感知，优化决策过程。规划阶段则利用反思结果制定长期策略，避免短视行为。实验证明，这一设计显著提升了LLM代理的导航性能，超越了现有最佳基线。
>
> https://arxiv.org/abs/2408.04168

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/Group_132.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/task_dataset.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/workflow_overview.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/prompt_example.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/SR_SPL.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/case_study1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/llava_distance.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/Group_115.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/no_plan.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/no_reflect.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/plain.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/Inner.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/CaP.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/ProgPrompt.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04168/CoT.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.04168](https://arxiv.org/abs/2408.04168)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)