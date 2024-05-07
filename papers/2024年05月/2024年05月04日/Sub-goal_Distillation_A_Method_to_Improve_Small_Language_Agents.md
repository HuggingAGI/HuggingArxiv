# 子目标蒸馏：提升小型语言代理性能的新方法

发布时间：2024年05月04日

`Agent` `人工智能` `决策制定`

> Sub-goal Distillation: A Method to Improve Small Language Agents

# 摘要

> 大型语言模型（LLMs）在交互式任务中展现出巨大潜力，但其高昂的计算成本和有限的调用次数限制了它们在长期交互任务如决策制定或连续任务场景中的实用性。为此，我们提出了一种将数十亿参数的LLM性能迁移至小型语言模型（仅7.7亿参数）的方法。该方法通过构建一个包含规划和执行两个模块的分层代理来实现：规划模块通过知识蒸馏从LLM学习生成子目标，执行模块则学习如何通过基本动作完成这些子目标。我们首先使用LLM为达成目标的路径标注一系列子目标，然后利用这些标注数据对两个模块进行微调。关键的是，推理过程中两个模块均无需实时访问LLM，从而大幅降低了与LLM交互的总体成本。在复杂的多任务交互文本环境ScienceWorld中，我们的方法在效率上超越了仅依赖基本动作的标准模仿学习，提升了16.7%。我们的分析显示，与其他基于LLM的方法相比，我们的方法更为高效。相关代码和用于蒸馏的标注数据已在GitHub发布。

> While Large Language Models (LLMs) have demonstrated significant promise as agents in interactive tasks, their substantial computational requirements and restricted number of calls constrain their practical utility, especially in long-horizon interactive tasks such as decision-making or in scenarios involving continuous ongoing tasks. To address these constraints, we propose a method for transferring the performance of an LLM with billions of parameters to a much smaller language model (770M parameters). Our approach involves constructing a hierarchical agent comprising a planning module, which learns through Knowledge Distillation from an LLM to generate sub-goals, and an execution module, which learns to accomplish these sub-goals using elementary actions. In detail, we leverage an LLM to annotate an oracle path with a sequence of sub-goals towards completing a goal. Subsequently, we utilize this annotated data to fine-tune both the planning and execution modules. Importantly, neither module relies on real-time access to an LLM during inference, significantly reducing the overall cost associated with LLM interactions to a fixed cost. In ScienceWorld, a challenging and multi-task interactive text environment, our method surpasses standard imitation learning based solely on elementary actions by 16.7% (absolute). Our analysis highlights the efficiency of our approach compared to other LLM-based methods. Our code and annotated data for distillation can be found on GitHub.

[Arxiv](https://arxiv.org/abs/2405.02749)