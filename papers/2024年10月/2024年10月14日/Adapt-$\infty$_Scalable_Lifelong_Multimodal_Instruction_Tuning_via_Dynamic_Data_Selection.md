# Adapt-$\infty$：利用动态数据选择，实现终身多模态指令调优的可扩展性

发布时间：2024年10月14日

`LLM应用` `人工智能`

> Adapt-$\infty$: Scalable Lifelong Multimodal Instruction Tuning via Dynamic Data Selection

# 摘要

> 视觉指令数据集因发布时间和任务组成不同，常含大量语义冗余的文本-图像对。这限制了多模态大型语言模型的终身适应能力。为此，我们提出通过数据选择重新定义终身指令调优（LiIT），模型自动从新旧数据集中挑选有益样本。基于经验分析，我们设计了Adapt-$\infty$，一种动态平衡效率与效果的多向自适应数据选择方法。通过伪技能集群和最佳数据选择器，我们确保训练样本的高效利用。同时，引入集群级永久数据修剪策略，避免计算负担过重。使用Adapt-$\infty$选择的样本训练，不仅减轻了稀有任务的灾难性遗忘，还促进了跨任务的前向转移，仅需少量原始数据。

> Visual instruction datasets from various distributors are released at different times and often contain a significant number of semantically redundant text-image pairs, depending on their task compositions (i.e., skills) or reference sources. This redundancy greatly limits the efficient deployment of lifelong adaptable multimodal large language models, hindering their ability to refine existing skills and acquire new competencies over time. To address this, we reframe the problem of Lifelong Instruction Tuning (LiIT) via data selection, where the model automatically selects beneficial samples to learn from earlier and new datasets based on the current state of acquired knowledge in the model. Based on empirical analyses that show that selecting the best data subset using a static importance measure is often ineffective for multi-task datasets with evolving distributions, we propose Adapt-$\infty$, a new multi-way and adaptive data selection approach that dynamically balances sample efficiency and effectiveness during LiIT. We construct pseudo-skill clusters by grouping gradient-based sample vectors. Next, we select the best-performing data selector for each skill cluster from a pool of selector experts, including our newly proposed scoring function, Image Grounding score. This data selector samples a subset of the most important samples from each skill cluster for training. To prevent the continuous increase in the size of the dataset pool during LiIT, which would result in excessive computation, we further introduce a cluster-wise permanent data pruning strategy to remove the most semantically redundant samples from each cluster, keeping computational requirements manageable. Training with samples selected by Adapt-$\infty$ alleviates catastrophic forgetting, especially for rare tasks, and promotes forward transfer across the continuum using only a fraction of the original datasets.

[Arxiv](https://arxiv.org/abs/2410.10636)