![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# 子目标蒸馏：提升小型语言代理效能的新方法
发布时间：2024年05月04日

`Agent应用`
> Sub-goal Distillation: A Method to Improve Small Language Agents
>
> 大型语言模型（LLMs）在交互任务中展现出巨大潜力，但其高昂的计算成本和有限的调用次数限制了它们在长期交互任务如决策制定或持续任务场景中的应用。为此，我们提出了一种将数十亿参数的LLM性能迁移至小型语言模型（7.7亿参数）的方法。该方法通过构建一个包含规划和执行两个模块的分层代理：规划模块通过知识蒸馏从LLM学习生成子目标，执行模块则学习如何通过基本动作实现这些子目标。我们首先使用LLM为完成目标的路径标注一系列子目标，然后利用这些标注数据对两个模块进行微调。关键的是，推理过程中两个模块均无需实时访问LLM，从而大幅降低了与LLM交互的总体成本。在复杂的多任务交互文本环境ScienceWorld中，我们的方法在效率上比基于基本动作的标准模仿学习高出16.7%。我们的分析显示了该方法相比其他基于LLM的方法的优越性。相关代码和用于蒸馏的标注数据已发布在GitHub上。
>
> https://arxiv.org/abs/2405.02749



- 论文原文: [https://arxiv.org/abs/2405.02749](https://arxiv.org/abs/2405.02749)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886