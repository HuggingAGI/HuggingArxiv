# RAP（检索增强规划器）：一种针对教学视频自适应程序规划的创新工具

发布时间：2024年03月27日

`RAG` `计算机视觉` `自动规划`

> RAP: Retrieval-Augmented Planner for Adaptive Procedure Planning in Instructional Videos

# 摘要

> 在教学视频中进行程序规划，意味着根据初始和目标状态的视觉信息来制定一系列动作步骤。尽管这方面已取得显著进展，但仍面临一些紧迫的挑战：(1) 自适应性问题：以往的研究通常假定动作步骤的数量是已知且不变的，这在现实世界的多变场景中并不实用。(2) 时间关联性：掌握步骤之间的时间关系对于制定合理可行的计划非常关键。(3) 注释代价：为教学视频添加详细的步骤标签或整体的动作分类标签，不仅要求高，而且非常耗费人力，这限制了其在大规模数据集上的应用。本研究提出了一种新颖而实用的自适应程序规划方法，其中程序的长度是灵活且不确定的。我们引入了名为检索增强规划器（RAP）的模型来应对这些挑战。RAP通过自回归模型架构灵活判断动作的结束点，并建立外部记忆模块，从训练视频中提取最相关的状态-动作对，以优化生成的程序。为了降低注释成本，RAP采用弱监督学习方法，通过生成动作步骤的伪标签，将训练范围扩展到其他相关的未标注视频。在CrossTask和COIN基准测试中，RAP的表现超越了传统固定长度模型，成为了自适应程序规划的一个强有力的基准方案。

> Procedure Planning in instructional videos entails generating a sequence of action steps based on visual observations of the initial and target states. Despite the rapid progress in this task, there remain several critical challenges to be solved: (1) Adaptive procedures: Prior works hold an unrealistic assumption that the number of action steps is known and fixed, leading to non-generalizable models in real-world scenarios where the sequence length varies. (2) Temporal relation: Understanding the step temporal relation knowledge is essential in producing reasonable and executable plans. (3) Annotation cost: Annotating instructional videos with step-level labels (i.e., timestamp) or sequence-level labels (i.e., action category) is demanding and labor-intensive, limiting its generalizability to large-scale datasets.In this work, we propose a new and practical setting, called adaptive procedure planning in instructional videos, where the procedure length is not fixed or pre-determined. To address these challenges we introduce Retrieval-Augmented Planner (RAP) model. Specifically, for adaptive procedures, RAP adaptively determines the conclusion of actions using an auto-regressive model architecture. For temporal relation, RAP establishes an external memory module to explicitly retrieve the most relevant state-action pairs from the training videos and revises the generated procedures. To tackle high annotation cost, RAP utilizes a weakly-supervised learning manner to expand the training dataset to other task-relevant, unannotated videos by generating pseudo labels for action steps. Experiments on CrossTask and COIN benchmarks show the superiority of RAP over traditional fixed-length models, establishing it as a strong baseline solution for adaptive procedure planning.

[Arxiv](https://arxiv.org/abs/2403.18600)