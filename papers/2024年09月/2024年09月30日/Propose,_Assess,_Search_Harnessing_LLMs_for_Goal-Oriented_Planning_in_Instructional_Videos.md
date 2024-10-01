# 提出、评估、搜索：借助 LLM 在教学视频中实现目标导向的规划

发布时间：2024年09月30日

`Agent` `人工智能`

> Propose, Assess, Search: Harnessing LLMs for Goal-Oriented Planning in Instructional Videos

# 摘要

> 面向目标的规划，即预测一系列动作以帮助智能助手从当前状态达到预设目标，对于日常程序任务的智能辅助至关重要。然而，这一过程因需全面理解任务的时间和层次结构，以及强大的推理和规划能力而充满挑战。传统方法依赖于大量数据训练，常导致数据偏差和泛化能力不足。为此，我们推出了VidAssist，一个专为教学视频中的零/少样本目标导向规划设计的集成框架。VidAssist利用大型语言模型（LLMs）作为知识库和评估工具，生成并评估行动计划，有效克服了从小规模、低多样性数据集中获取程序知识的难题。此外，VidAssist采用广度优先搜索算法，结合专门设计的价值函数组合，评估每一步的预测动作，确保最佳计划生成。实验证明，VidAssist不仅为视觉规划辅助（VPA）和程序规划（PP）等不同规划场景提供统一框架，还在零样本和少样本设置中表现卓越。具体来说，我们的少样本模型在COIN数据集上的VPA任务中比先前最先进方法高出+7.7%，在PP任务中高出+4.81%，同时预测了4个未来动作。代码和模型已公开，访问地址为https://sites.google.com/view/vidassist。

> Goal-oriented planning, or anticipating a series of actions that transition an agent from its current state to a predefined objective, is crucial for developing intelligent assistants aiding users in daily procedural tasks. The problem presents significant challenges due to the need for comprehensive knowledge of temporal and hierarchical task structures, as well as strong capabilities in reasoning and planning. To achieve this, prior work typically relies on extensive training on the target dataset, which often results in significant dataset bias and a lack of generalization to unseen tasks. In this work, we introduce VidAssist, an integrated framework designed for zero/few-shot goal-oriented planning in instructional videos. VidAssist leverages large language models (LLMs) as both the knowledge base and the assessment tool for generating and evaluating action plans, thus overcoming the challenges of acquiring procedural knowledge from small-scale, low-diversity datasets. Moreover, VidAssist employs a breadth-first search algorithm for optimal plan generation, in which a composite of value functions designed for goal-oriented planning is utilized to assess the predicted actions at each step. Extensive experiments demonstrate that VidAssist offers a unified framework for different goal-oriented planning setups, e.g., visual planning for assistance (VPA) and procedural planning (PP), and achieves remarkable performance in zero-shot and few-shot setups. Specifically, our few-shot model outperforms the prior fully supervised state-of-the-art method by +7.7% in VPA and +4.81% PP task on the COIN dataset while predicting 4 future actions. Code, and models are publicly available at https://sites.google.com/view/vidassist.

[Arxiv](https://arxiv.org/abs/2409.20557)