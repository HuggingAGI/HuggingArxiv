# SCHEMA 研究表明，在解析教学视频中的程序规划时，状态变化起到关键作用。

发布时间：2024年03月03日

`Agent`

> SCHEMA: State CHangEs MAtter for Procedure Planning in Instructional Videos

> 本文针对指导视频中的程序规划难题展开研究，旨在面对部分可视状态信息，规划出一套以目标为导向的动作步骤流程。目前虽已有研究仅依赖序列级别的标注成功实现步骤的顺序建模，但却忽略了状态在整个过程中所起的关键作用。在此，我们强调在指导视频程序规划中，状态变化（SCHEMA）扮演着核心角色。我们致力于通过深入探究步骤与程序内各状态间的因果关联，构建更为有序的状态空间。为此，我们创新地将每一步骤明确表述为状态改变，并在执行过程中持续追踪这些变化。在步骤表达上，我们借助大型语言模型（LLMs）蕴含的常识知识，通过精心设计的链式思考提示方式，详细描绘步骤导致的状态变迁。同时，我们运用跨模态对比学习技术将可视状态观测与语言描述的状态进行对应，并运用LLMs生成的状态描述精确模拟程序中的中间状态过程。实验证明，在CrossTask、COIN和NIV等基准数据集上，我们提出的SCHEMA模型不仅取得了当前最优性能，还生成了具有解释力的可视化结果。

> We study the problem of procedure planning in instructional videos, which aims to make a goal-oriented sequence of action steps given partial visual state observations. The motivation of this problem is to learn a structured and plannable state and action space. Recent works succeeded in sequence modeling of steps with only sequence-level annotations accessible during training, which overlooked the roles of states in the procedures. In this work, we point out that State CHangEs MAtter (SCHEMA) for procedure planning in instructional videos. We aim to establish a more structured state space by investigating the causal relations between steps and states in procedures. Specifically, we explicitly represent each step as state changes and track the state changes in procedures. For step representation, we leveraged the commonsense knowledge in large language models (LLMs) to describe the state changes of steps via our designed chain-of-thought prompting. For state change tracking, we align visual state observations with language state descriptions via cross-modal contrastive learning, and explicitly model the intermediate states of the procedure using LLM-generated state descriptions. Experiments on CrossTask, COIN, and NIV benchmark datasets demonstrate that our proposed SCHEMA model achieves state-of-the-art performance and obtains explainable visualizations.

[Arxiv](https://arxiv.org/abs/2403.01599)