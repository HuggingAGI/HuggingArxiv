# 机器人模拟生成效果的评估

发布时间：2024年10月10日

`Agent` `机器人` `人工智能`

> On the Evaluation of Generative Robotic Simulations

# 摘要

> 由于获取真实数据的难度，机器人模拟变得至关重要，尤其是在并行训练和模拟到现实的转移中，这凸显了可扩展模拟任务的重要性。基础模型在自主生成机器人任务方面表现出色，但这也带来了如何有效评估这些生成任务的新挑战。为此，我们设计了一个综合评估框架，涵盖质量、多样性和泛化性三个核心方面。我们通过大型语言模型和视觉语言模型评估任务的真实性和轨迹的完整性，通过任务描述的文本相似性和世界模型损失来衡量多样性，并通过策略在未见任务上的零样本泛化能力来评估任务级泛化。实验结果表明，我们的框架与人类评估高度一致，证实了其可行性和有效性。研究发现，虽然某些方法可以实现质量和多样性，但没有一种方法能在所有指标上表现优异，这提示我们需要更多关注这些指标的平衡。此外，我们的分析还揭示了当前工作普遍面临的低泛化能力问题。更多信息请访问我们的匿名网站：https://sites.google.com/view/evaltasks。

> Due to the difficulty of acquiring extensive real-world data, robot simulation has become crucial for parallel training and sim-to-real transfer, highlighting the importance of scalable simulated robotic tasks. Foundation models have demonstrated impressive capacities in autonomously generating feasible robotic tasks. However, this new paradigm underscores the challenge of adequately evaluating these autonomously generated tasks. To address this, we propose a comprehensive evaluation framework tailored to generative simulations. Our framework segments evaluation into three core aspects: quality, diversity, and generalization. For single-task quality, we evaluate the realism of the generated task and the completeness of the generated trajectories using large language models and vision-language models. In terms of diversity, we measure both task and data diversity through text similarity of task descriptions and world model loss trained on collected task trajectories. For task-level generalization, we assess the zero-shot generalization ability on unseen tasks of a policy trained with multiple generated tasks. Experiments conducted on three representative task generation pipelines demonstrate that the results from our framework are highly consistent with human evaluations, confirming the feasibility and validity of our approach. The findings reveal that while metrics of quality and diversity can be achieved through certain methods, no single approach excels across all metrics, suggesting a need for greater focus on balancing these different metrics. Additionally, our analysis further highlights the common challenge of low generalization capability faced by current works. Our anonymous website: https://sites.google.com/view/evaltasks.

[Arxiv](https://arxiv.org/abs/2410.08172)